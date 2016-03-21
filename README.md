# impress-plugin

I am looking for PHP expertise to customize a php page.

I am using the IMPress listings plugin (formerly WP Listings) to display real estate listings, but can't get the listing pages to display a sidebar. (The sidebar is selected in Avada page options.)

This is the result: http://lewisedc.com/wordpress3/edcproperty/new-property/

But I want a sidebar on the side, like this: http://lewisedc.com/wordpress3/page-with-a-sidebar/

I have received some direction from plugin and themeforest support, but Avada doesn't call the sidebar in the way the plugin expects, and further customization of the single-listing.php file is beyond the scope of what they can provide.

Would love to hire someone who could help me finish customizing this plugin. 

STEPS TAKEN:

1) Customized the plugin file (single-listing.php) and put it in my active theme folder (wp-content/themes/Avada-Child-Theme/)

2) Tried calling a custom sidebar into the single-listing.php file. Problem: It appears at the top of div id="sidebar", not outside of it. Code for that is here: 
    [<div id="sidebar" style="<?php echo $sidebar_css; ?>"><?php generated_dynamic_sidebar(); ?></div>]

LINKS:

IMPress Listings plugin page > https://wordpress.org/plugins/wp-listings/

Thread describing custom sidebar into custom template > https://theme-fusion.com/forums/topic/calling-custom-sidebar-into-custom-template/
