# Polymer Github Ribbon

## Installation

```
bower install reggi/polymer-github-ribbon --save
```

## Usage

Drop the following lines within the `<head>` tag.

	<script src="./bower_components/platform/platform.js"></script>
	<link rel="import" href="./bower_components/polymer-github-ribbon/github-ribbon.html">

To create a new banner use the `<github-ribbon>` tag.

```
<github-ribbon href="https://github.com/reggi/polymer-github-banner"></github-ribbon>
```

## Attributes

### `href` 
 
The url to the github repo. (required)

### `color`
  
The color of the ribbon.

* red
* green
* black (default)
* orange
* gray
* white

### `corner`

Which side of the page the ribbon will show on.

* right (default)
* left

Source: [Github Ribbons](https://github.com/blog/273-github-ribbons)