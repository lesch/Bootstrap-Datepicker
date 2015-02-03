# [Bootstrap-Datepicker](http://projects.lsch.ru/datepicker/)
Bootstrap Datepicker (bootstrap-datepicker.js) is a plugin for Twitter Bootstrap providing flexible tool to work with dates and dates ranges by selecting dates from popup calendar.
You can create your own powerful instrument operating options and event listeners.
Original by [Stefan Petre](http://www.eyecon.ro/bootstrap-datepicker), renovate by [Lev Leschiner](http://leschiner.ru).
Compatible with Bootstrap v3+.

Website and tutorial: http://projects.lsch.ru/datepicker/
Download: [datepicker.zip](http://projects.lsch.ru/datepicker/datepicker.zip)

## Installation
[Download](http://projects.lsch.ru/datepicker/datepicker.zip) plugin or clone the repo: `git clone https://github.com/lesch/Bootstrap-Datepicker.git`.
Include js and css into your code:

    <!-- CSS including -->
    <link rel="stylesheet" href="/path/to/datepicker.css">

    <!-- JS including -->
    <script src="/path/to/bootstrap-datepicker.js" type="text/javascript"></script>

**Notice!** This plugin is created to work with jQuery, but jQuery isn`t included in the bundle, so you need [download and install jQuery](http://jquery.com/download/) by yourself.

## Usage

All options, events and hooks provided on the demo page [on my website](http://projects.lsch.ru/datepicker/) or in the bundle (datepicker.html).

## Change log

**02/02/2015**
* As soon as main author of this extension don`t change it from 12/03/2013, some issues based on changes of Bootstrap core was fixed
* CSS minor fixes
* More detailed tutorial (example list) created
* onRender moved from Events to the Options (because it is actually not event)
* onStart option added
* autoClose option added