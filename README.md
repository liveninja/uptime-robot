# Uptime Robot #
Contributors: @briancwelch
Requires at least: WordPress 3.7
Tested up to: WordPress 4.0


A simple WordPress dashboard widget that shows you the current uptime stats of your Uptime Robot monitored websites.

## Description ##
This plugin will allow you to enter your Uptime Robot API key and will provide a dashboard widget that will show you each of your current monitors, the monitor ID, their type, ratio and will provide a link to each of the sites in question.

*Each listing is also color coded visually depending on its status, providing much needed information at a quick glance.*


## Installation ##
Either upload the zip in the plugins manager, or install using the WordPress dashboard and activate the plugin.
Once you have activated the plugin, visit the Uptime Robot settings submenu, and enter your Uptime Robot API key, and save your changes.

*The widget and monitor listing will be displayed on your WordPress dashboard.*


## Frequently Asked Questions ##
**Q: What is Uptime Robot?**
*Uptime Robot provides real time site monitoring for multiple different types of connections and data types.*

**Q: Do I need to sign up for Uptime Robot to get an API key?**
*Yes.  You will not be able to obtain an API key otherwise.*

**Q: Does Uptime Robot cost anything?**
*No.  They have free accounts and options.*

**Q: Are you affiliated with Uptime Robot?**
*No.  I just thought others may enjoy this plugin.*

**Q: Does it cost anything to use this plugin?**
*No.  However, you may donate to help fund further development if you find the plugin useful.*


## Screenshots ##
![Alt text](https://github.com/briancwelch/uptime_robot/blob/screenshots/screenshot-1.png?raw=true "Dashboard Widget")

![Alt text](https://github.com/briancwelch/uptime_robot/blob/screenshots/screenshot-2.png?raw=true "Settings")


## Changelog ##
**v1.0.7**
- Fix an issue with $port_tip being undefined which caused an error in the debugger.
- Fix spelling and grammar mistakes in the documentation.

**v1.0.6**
- Code Cleanup [See also: WordPress PHP Coding Standards.](http://make.wordpress.org/core/handbook/coding-standards/php/)
- Sanitize the URL of the panel images.
- Update readme.txt for better legibility and markdown.
- Tagging as WordPress 4.0 ready.

**v1.0.5**
- Added icons and tooltips for the monitor status and removed status text in an order to maximize widget real estate.
- Added option to toggle the display of the monitor ID.
- Added option to toggle the display of the uptime ratio.
- Added option to toggle the display of the monitor type.
- Cleaned up tooltip styling.

**v1.0.4**
- Fix API key sanitization.

**v1.0.3**
- Code and CSS cleanup.  
- Revised tooltip function so that tooltips are displayed only on monitored ports.  
- Updated screenshot.

**v1.0.2**
- Add tooltips to show the port being monitored if the monitor subtype is set to "Port."

**v1.0.1**
- Fix error with loading CSS file if plugin directory name was changed.

**v1.0.0**
- Initial version.


## Upgrade Notice ##
**1.0.6**
Upgrading to 1.0.6 fixes a security issue with sanitizing the panel image URLs, and is ready for WordPress 4.0.

**1.0.5**
Upgrading to 1.0.5 enables a few additional display options.

**1.0.4**
Upgrading to 1.0.4 fixes a security issue by properly sanitizing the API Key setting.


## Translations ##
* English: Default - Always included.
* German: Secondary - In der Regel enthalten.


## Credits ##
* Thanks to David Sal for the idea.
* [Uptime Robot](http://www.uptimerobot.com/) for providing a wonderful free service.
* @emiliorcueto for various bugfix(es).


## Additional Info ##
No additional information is available at the moment.