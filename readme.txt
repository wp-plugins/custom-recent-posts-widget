=== Custom Recent Posts Widget ===
Contributors: prasannasp 
Donate link: http://www.prasannasp.net/
License: GPLv3
License URI: http://www.gnu.org/copyleft/gpl.html
Tags: recent posts, category, categories, widget, post list, exclude, include
Requires at least: 3.1
Tested up to: 3.4.1
Stable tag: 2.0

A widget to show recent posts list based on categories or tags

== Description ==
This plugin creates a new widget which lets you show a list of recent posts based on categories or tags. This is a must have plugin if you want to exclude some categories in recent posts widget or if you want to show recent posts based on tags. By default the wordpress recent posts widget shows a posts from all category. But this plugin gives you more power to customize your recent posts widget.

You can see the working example of this plugin on Kennneth John Odle's <a href="http://blog.kjodle.net/">blog</a>. See these widgets in sidebar,

<ul>
<li><a href="http://blog.kjodle.net/#custom-recent-posts-2">WordPress Tutorials</a></li>
<li><a href="http://blog.kjodle.net/#custom-recent-posts-3">WordPress Plugin Tutorials</a></li>
<li><a href="http://blog.kjodle.net/#custom-recent-posts-4">Graphene Tutorials</a></li>
</ul>

Visit <a href="http://www.prasannasp.net/wordpress-plugins/">this page</a> for more <strong>WordPress Plugins</strong> from the developer.

A special thanks to <a href="http://blog.kjodle.net/">Ken</a> and <a href="http://www.joshlobe.com">Josh</a> for testing the code.

== Installation ==

1. Extract the contents of the .zip archive

2. Upload the `custom-recent-posts-widget` folder to your `wp-content/plugins` directory.
     
3. Activate the plugin through the 'Plugins' menu in WordPress.

4. Go to Appearance --> Widgets to add the widget to any widgetized areas.

== Screenshots ==

1. Custom Recent Posts Widget
2. Custom Recent Post Widget when added to sidebar on widget menu. Here the number of posts to show is set to 6 and only the 'Wordpress' category is selected
3. Custom Recent Post Widget showing a list of 6 recent posts from the category 'Wordpress'
4. Custom Recent Post Widget in Kennneth John Odle's blog
5. Custom Recent Posts by Tags Widget

== Frequently Asked Questions ==

= How to style the widget? =

The widgets inherit the style of default WordPress Recent Posts widget. You can use `.crpw-item` and `.crpw-tag-item` CSS class to style Custom Recent Posts Widget and Custom Recent Posts by Tags Widget respectively. 

<strong>Example</strong>

`.crpw-item {
    font-weight: bold;
    font-size: 14px;
    list-style: disc inside;
}`

== Changelog ==

= 2.0 =
* Added Custom Recent Posts by Tags Widget. You can show recent posts based on tags.
* Removed style sheet and changed classname to `widget_recent_entries`. So, widget will inherit the style of default WordPress Recent Posts widget.

= 1.1 =
* Changed class names
* Updated style sheet
* Using `crpw_register_widgets` function to register the widget
* Added another screen shot

= 1.0 =
* Initial public release

== Upgrade Notice ==
*No Upgrade Notice so far.
