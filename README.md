# Minimal HTML Project Template

by [Michael Guerra](http://msguerra74.com)

This is a minimal html project template and nothing more.

## Additional Options

### 404 File Not Found

Create a file called 404.html with the appropriate File Not Found content.

### Apache Server Configs

- Download the [.htaccess](https://raw.githubusercontent.com/h5bp/html5-boilerplate/master/dist/.htaccess) file, edit it as necessary, and place in the root of the project.

### Canonical Link

Add the following link inside the html head section with the appropriate url to that page.

```html
<link rel="canonical" href="http://website.com/">
```

### Google Analytics

Add the following script right before the closing of the html body section, replacing 'UA-xxxxxxxx-x' with the appropriate Google Analytics ID.

```html
<script>
  window.ga=function(){ga.q.push(arguments)};ga.q=[];ga.l=+new Date;ga('create','UA-xxxxxxxx-x','auto');ga('send','pageview')
</script>
<script src="https://www.google-analytics.com/analytics.js" async defer></script>
```

### Icons

- Use an [online icon generator](http://realfavicongenerator.net) to create every possible icon:

Alternately, create the icons manually as listed out below:

#### Apple Touch Icon

Create an icon image called apple-touch-icon.png with the dimensions of 152x152 in the root of the project.

Then add the following link inside the html head section.

```html
<link rel="apple-touch-icon" href="apple-touch-icon.png">
```

#### Favicon

Create an icon image called favicon.ico with three embedded dimensions of 16x16, 32x32, and 48x48 in the root of the project.

#### Windows Tiles

Create two icon image called tile.png and tile-wide.png with the dimensions of 558x558 and 558x270 respectively in the root of the project.

Then create a file called browserconfig.xml with the appropriate icon tile information (see example below).

```xml
<?xml version="1.0" encoding="utf-8"?>
<browserconfig>
  <msapplication>
    <tile>
      <square70x70logo src="tile.png"/>
      <square150x150logo src="tile.png"/>
      <wide310x150logo src="tile-wide.png"/>
      <square310x310logo src="tile.png"/>
    </tile>
  </msapplication>
</browserconfig>
```

### Robots

Create a file called robots.txt with the appropriate robot content (see example below).

```txt
Sitemap: http://website.com/sitemap.xml

User-agent: *
Disallow:
```

### RSS Feed

Create a file called feed.xml with the appropriate feed content (see example below).

```xml
<?xml version="1.0" encoding="utf-8"?>
<feed xmlns="http://www.w3.org/2005/Atom">
  <title>Website title</title>
  <link rel="self" href="http://website.com/feed.xml" />
  <link href="http://website.com/" />
  <updated>2017-07-07T16:13:04-05:00</updated>
  <id>http://website.com/</id>
  <author>
    <name>Owner Name</name>
    <email>owner@email.com</email>
  </author>
</feed>
```

Then add the following link inside the html head section.

```html
<link rel="alternate" href="feed.xml" title="Website title Feed" type="application/atom+xml">
```

### Sitemap

Create a file called sitemap.xml with the appropriate sitemap content (see example below).

- Find additional information on how to [build a sitemap](https://support.google.com/webmasters/answer/183668)

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>http://website.com/</loc>
  </url>
</urlset>
```

Add the following link inside the html head section.

```html
<link rel="sitemap" href="sitemap.xml" title="Website title Sitemap" type="application/xml">
```

## MIT License (MIT)

Copyright 2017 Michael Guerra

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.