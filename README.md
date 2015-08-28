# sanilize.css

> A merge between [sanitize.css][sanitize] by [Jonathan Neal][jonathan] and [normalize.css][normalize] by [Necolas][necolas]

[jonathan]:https://github.com/jonathantneal
[sanitize]:https://github.com/10up/sanitize.css
[necolas]:https://github.com/necolas
[normalize]:https://github.com/necolas/normalize.css

Render elements consistently. Style with best practices.

## Installation

For now:
[Download it](https://raw.githubusercontent.com/filipelinhares/sanilize.css/master/sanilize-min.css) and install manually

## Highlights

- CSS inheritance is universal so that styles are easier to control ([code](sanitize.scss#L94-L108)).
- The box model is more intuitive with border-box ([reference](http://www.paulirish.com/2012/box-sizing-border-box-ftw/)) ([reference](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/)) ([code](sanitize.scss#L135)).
- Smaller font-sizes display consistently across browsers ([reference](https://github.com/servo/servo/issues/3423#issuecomment-56321664)) ([code](sanitize.scss#L68-L70)).
- Monospace fonts render consistently ([reference](http://code.stephenmorley.org/html-and-css/fixing-browsers-broken-monospace-font-handling/)) ([code](sanitize.scss#L152-L159)).
- Border width works as expected ([reference](https://developer.mozilla.org/en-US/docs/Web/CSS/border-style#Values)) ([code](sanitize.scss#L116-L123)).
- Text selections containing a drop shadow remain legible ([reference](https://twitter.com/miketaylr/status/12228805301)) ([code](sanitize.scss#L202-L207)).
- Content may be hidden from the screen but not screenreaders ([reference](http://www.paciellogroup.com/blog/2012/05/html5-accessibility-chops-hidden-and-aria-hidden/)) ([reference](https://www.drupal.org/node/897638)) ([code](sanitize.scss#L209-L220)).
To give you even more control, [sanilize.css](sanilize.css) allows you to define your own defaults for box-sizing, font family, monospace font family, text rendering, selection background color, and smaller font size - all without over-declaring them later.

## Support

At present, we support the current and previous major releases of popular web browsers. When a new version is released, we begin supporting that version and stop supporting the third most recent version.

These browsers currently include Android 4.3-4.4+, Chrome 39-40+, Firefox 34-35+, Internet Explorer 10-11+, iOS 7-8+, Safari 7-8+, Windows Phone 8.1+.

## License

**sanilize.css** is dedicated to the [public domain](LICENSE.md).
