# moodle-php-fpm: A Moodle PHP FPM Environment

A Moodle PHP FPM environment configured for Moodle deployment based on the [Official Moodle PHP Apache image](https://hub.docker.com/r/moodlehq/moodle-php-apache).


# Features

* Preconfigured with all php extensions required for Moodle development and all database drivers
* Serves wwroot configured at /var/www/html/

# Directories

To faciliate testing and easy setup the following directories are created and owned by www-data by default:
* `/var/www/moodledata`
* `/var/www/phpunitdata`
* `/var/www/behatdata`
* `/var/www/behatfaildumps`

