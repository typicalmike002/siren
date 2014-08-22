# Table of Contents for the CSS Directory #
## As of Siren 3.2 ##

### DIRECTORIES ###
1. POLYFILLS
	- Contains polyfills necessary for maintaining consistency in browser styles
	- Contents: boxsizing.htc
2. SASS
	- Contains the .scss files that are processed into .css
	- TOC included

### FILES ###
1. basic.css
	- Contains the Safe CSS styles served to all browsers inline in the <head>
	- Generated from a SCSS file
2. enhanced.css
	- Contains the enhanced styles that are applied following a test.
	- Developed responsively and mobile-first
	- Generated from a SCSS file
3. enhanced-ie.css
	- Served to IE8 and IE7 browsers
	- Same as enhanced.css but without the media queries as that code is generated by respond.js for these browsers
	- Can contain IE specific rules if necessary
	- Generated from a SCSS file