## Synopsis

A repo for tracking and maintaining the presentation layer code - all CSS that relates to a particular vertical (or product) will live here, be edited here, and be compiled from here

## Code Example
~~~
@import "nameOfSCSSfile"
~~~
- imports modular SCSS files into a master for each (for example importing widget styles into the ICE4E master file)

~~~
$variablename
~~~ 
- create variables for re-use inside of SCSS files

## Motivation

Compiling and storing base SCSS files will help maintain a clean codebase. Styles should be modular and organized according to 1) vertical and 2) feature and be implemented as necessary. All SCSS should be compiled via Compass and Grunt into a single CSS file per deployment.

## Installation

SASS and Compass are dependencies for development. Both require Ruby.

SASS install: http://sass-lang.com/install

Compass install: http://compass-style.org/install/

## API Reference

SASS: http://sass-lang.com/documentation/file.SASS_REFERENCE.html

Compass: http://compass-style.org/help/documentation/

## Using Compass with Grunt

use grunt-contrib-compass and grunt-contrib-watch in development to edit and compile SCSS files to the master CSS directory (some configuration may be required) 

https://github.com/gruntjs/grunt-contrib-compass (includes sample files and examples)

https://github.com/gruntjs/grunt-contrib-watch

Using Terminal: cd to project; run Grunt watch