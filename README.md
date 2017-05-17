# JSON Feed for Jekyll

A simple feed file that follows the [1.0 spec](https://jsonfeed.org/version/1) of the JSON Feed standard established by [Manton Reece](http://manton.org/) and [Brent Simmons](http://inessential.com/).

## Installation
Copy the `feed.json` file to the root directory of your Jekyll install.

Add the following line to your `head.html` (or similar theme file where the `<head>` section of your site is defined.

```
<link rel="alternate" title="My Feed" type="application/json" href="https://example.org/feed.json" />
```
(replace My Feed and example.org with your own values)

If your server is not configured to serve JSON files, you might need to add this to your .htaccess file:

```
AddType application/json .json
```