# pagespeed_list_thaccess
...
<IfModule pagespeed_module>
ModPagespeed on
ModPagespeedEnableFilters extend_cache,combine_css,combine_javascript,collapse_whitespace,move_css_to_head
ModPagespeedEnableFilters canonicalize_javascript_libraries
ModPagespeedEnableFilters collapse_whitespace
ModPagespeedEnableFilters rewrite_images
ModPagespeedEnableFilters remove_comments

</IfModule>
...
