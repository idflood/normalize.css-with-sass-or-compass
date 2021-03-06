## The Compass port of normalize.css

This project is the Sass/Compass port of normalize.css. It aims to use the best
partials from Compass to make normalize even easier to integrate with your
website. To learn about why Normalize.css is so amazing, skip to the
"normalize.css" section below.

This Sass/Compass port currently utilizes:

* Legacy IE support variables
* CSS3 Box Sizing mixin
* Vertical Rhythm mixins

In addition, Normalize.css has 2 major versions: version 2 (without legacy
browser support) and version 1 (with support for IE 6/7, etc.) This Compass port
combines the two versions into one file so that you can easily toggle between
the two versions using Compass' `$legacy-support-for-ie7` variable.

Did a client wait until the last minute to mention their CEO uses IE 7? Simply
set `$legacy-support-for-ie7` to `true` and recompile your Sass files.

For the record, there are actually other Compass ports as well. Including:

* https://github.com/waynegraham/compass-normalize-plugin
* https://github.com/ksmandersen/compass-normalize
* https://github.com/hail2u/normalize.scss
* https://github.com/kristerkari/normalize.scss

Some of the above projects make normalize into a Sass partial. That makes them
impossible to use in the recommended way (by copying the file into your website
and customizing for your needs.)

# normalize.css v2.0.1

Normalize.css is a customisable CSS file that makes browsers render all
elements more consistently and in line with modern standards. We researched the
differences between default browser styles in order to precisely target only
the styles that need normalizing.

[Check out the demo](http://necolas.github.com/normalize.css/2.0.1/test.html)

## What does it do?

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Explains what code does using detailed comments.

## How to use it

Normalize.css is intended to be used as an alternative to CSS resets.

It's suggested that you read the `normalize.css` file and consider customising
it to meet your needs. Alternatively, include the file in your project and
override the defaults later in your CSS.

For more information about how to use it, see the [About normalize.css article](http://nicolasgallagher.com/about-normalize-css/).

## Browser support

* Google Chrome
* Mozilla Firefox 4+
* Apple Safari 5+
* Opera 12+
* Internet Explorer 8+

## Contribute

Please read my [issue
guidelines](https://github.com/necolas/issue-guidelines).

## Acknowledgements

Normalize.css is a project by [Nicolas Gallagher](http://github.com/necolas)
and [Jonathan Neal](http://github.com/jonathantneal).

This Compass port is a project by [John Albin Wilkins](http://john.albin.net).
