Make Bookmarklet
================

Overview
--------

Converts a JavaScript file into a `javascript:` URL that can be used as a [bookmarklet](https://en.wikipedia.org/wiki/Bookmarklet). The bookmarklet text is inserted into the current file as a comment on the first line for reference or to copy out later. It is also immediately copied to the clipboard (which can be disabled with a setting).

This is an unabashed rip-off of [John Gruber's Perl version](http://daringfireball.net/2007/03/javascript_bookmarklet_builder), just made to work natively in Sublime Text 3 and 4.

Usage
-----

From the Command Palette, search for `Make Bookmarklet`.

Or, under the menu `Tools > Make Bookmarklet`.

Example Bookmarklet
-------------------

- [Log The Focused Element](https://gist.github.com/gillibrand/e240b129ae748b9e2291)

Limitations
-----------

1. Does not strip `/* multi-line comments*/`, so don't use them.
