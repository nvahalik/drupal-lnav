# Overview

Drupal log file formats for [lnav][1]. lnav is a text-based log file viewer and analyzer. It can parse log files and make them searchable by SQL queries and regular expressions.

This log format provides two definitions:

1. Drupal Access log format
2. Drupal Watchdog syslog format

It will pull out relevant fields into the appropriate tables so that they can be searched and filtered on.

# Installation

You can install this by downloading the definition and running the command `lnav -i path/to/drupal.json`.

# Notes

You will probably need to be using the latest version of lnav to make this work.


[1]: http://lnav.org