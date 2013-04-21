About
=====

This module provides integration with Rollbar. Rollbar provides a central
point for managing code errors and warnings on your site. Users can easlily
track when errors begin to occur and how often.

Combined with client infomation. Like, browser, page plugins etc it can be
very powerful at aiding development.

This is not an official Rollbar module, this is currently also not on Drupal.org
as there is some code in the module from the setup process at https://rollbar.com/docs/items_js/
that I can't varify is licensed under the GPL.

Sign up for an account at https://rollbar.com/docs/items_js/


Features
========

This module currently supports

* Configurable PHP library path.
* Configurable access keys.
* Configurable environment (production, staging development etc)
* PHP Exception handler.
* PHP Error handler.
* Watchdog error handler
* Ignore PHP watchdog errors. (Don't send these to Rollbar)
* Ability to turn off native PHP handlers and send all watchdog errors
* JavaScript integration (send JS errors/exceptions to Rollbar.com)


Installation
============

1. Clone this repository. `git clone git@github.com:thepearson/drupal_rollbar.git`
2. Copy the rollbar directory to the modules folder in your installation.
3. Enable the module using Administer -> Modules (`admin/modules`)
4. Download rollbar.php from https://github.com/rollbar/rollbar-php and place it in `sites/all/libraries/rollbar/rollbar.php`


Configuration
=============

All configuration settings can be found under admin/config/development/rollbar
once the module is enabled.



