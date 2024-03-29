# API Log Pro.
A simple plugin to log WordPress Rest API Requests.

[![Build Status](https://travis-ci.com/bhubbard/api-log-pro.svg?token=kkcazsQEFZQ5dR7MwDsz&branch=master)](https://travis-ci.com/bhubbard/api-log-pro)

* **Contributors:** [bhubbard](https://profiles.wordpress.org/bhubbard)
* **Tags:** wp rest api, rest api, wp api, api, json, json api, logging
* **Requires at least:** 5.0
* **Tested up to:** 5.8.1
* **Stable tag:** 0.0.8
* **License:** GPLv3 or later
* **License URI:** http://www.gnu.org/licenses/gpl-3.0.html


## Description

This plugin enables logging of all calls to the WordPress REST API. You can view all logs from the WordPress Admin under **API Log Pro**.

### API Access to Logs

You can use the WordPress api to view the logs if you have `manage options` permissions as a WordPress User. Here is the endpoint:

```/wp-json/api-log-pro/v1/logs```

### WP-CLI Support

This plugin offers some basic wp-cli support. You can use the following command to delete all the logs in the db.

```wp api-log-pro delete```

## Installation ##

1. Copy the `api-log-pro` folder into your `wp-content/plugins` folder
2. Activate the `API Log Pro` plugin via the plugin admin page

## Changelog ##

Please see [CHANGELOG.MD](CHANGELOG.md)
