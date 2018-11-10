8.x-2.x-dev
================================================================================

Background
--------------------------------------------------------------------------------
The Drupal 7 version of this module used a forked version of the Sendgrid
library due to the library's dependency on a sunsetted version of Guzzle (3.x).
The updated version of the library no longer has this dependency. Additionally,
it includes an update to support v3 of the Sendgrid API.

This latest iteration of the Drupal 8 version of the Sendgrid Integration
module now supports v3 of the API and will move back to the version of the
library that is supported and sponsored by Sendgrid.

Github Repository:
https://github.com/sendgrid/sendgrid-php

Major changes
--------------------------------------------------------------------------------
* Switch to Sendgrid's official PHP library (sendgrid/sendgrid)
* Remove left over D7 module files that are no longer needed in D8.
* Requires PHP 5.6 or greater

Dependencies (loaded via composer)
--------------------------------------------------------------------------------
* MailSystem Module (https://www.drupal.org/project/mailsystem)
* Sendgrid Library (sendgrid/sendgrid)
