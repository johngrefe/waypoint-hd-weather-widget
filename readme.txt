=== Plugin Name ===
Contributors: JohnGrefe
Tags: widgets, sidebar, shortcode, openweathermap, weather, weather widget, forecast, global
Requires at least: 3.5
Tested up to: 3.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

The Waypoint HD Weather Widget, HD weather, that changes with the outside conditions, over 49 Different "Feels"

== Description ==

This plugin uses HD 331dp images, in beautiful cirlces, to display weather for your location.  

Use the built in widget or add it somewhere else with this shortcode: (all settings shown)

`[waypoint-weather location="Montreal" units="F" size="tall" override_title="MTL" forecast_days=2 hide_stats=true background=http://urltoanimage.jpg]`

Settings:

*   Location: Enter like Montreal, CA or just Montreal. You may need to try different variations to get the right city
*   Units: F (default) or C
*   Size: wide (default) or tall
*   Override Title: Change the title in the header bar to whatever, sometimes it pulls weather from a close city
*   Forecast Days: How many days to show in the forecast bar
*   Hide stats: Hide the text stats like humidity, wind, high and lows, etc
*   Background: URL to an image that will be used as the background of the entire widget, you probably don't want this as you want the css to load the dynamic images.

All weather data is provided by http://openweathermap.org and is cached for one hour.


== Installation ==

1. Add plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Use shortcode or widget


== Screenshots ==

1. Basic tall layout

== Release History ==

= .1 =
First release for proof.  

Lookup the condition code that the plugin is displaying while running such as "Clear Skys" here, then change file name to that code, ex "800.png". http://bugs.openweathermap.org/projects/api/wiki/Weather_Condition_Codes

 
