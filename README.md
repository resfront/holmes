# <img alt="Holmes.js" src="http://puu.sh/pgBsm/c63088a07f.png" height="50px"></img>

> simple search based on the dom

[![Build Status](https://travis-ci.org/Haroenv/holmes.svg?branch=gh-pages)](https://travis-ci.org/Haroenv/holmes)[![npm version](https://badge.fury.io/js/holmes.js.svg)](https://www.npmjs.com/package/holmes.js)

## Installation

```
$ npm install --save holmes.js
```

After which you can add it in your page with i.e. browserify or loading the module in a different script tag.

You have to make sure that you have a `css` rule for the class `.hidden` that hides elements however you want. One option is to have this:

```css
.hidden {
  display: none;
}
```

but this could be any `css` you want.

## Usage

[demo](https://haroen.me/holmes/)

```js
holmes({
  input: '.search input', // queryselector for the input
  find: '.results article', // queryselector for element to search in
});
```

### Questions?

Compatible up to IE9.

Let me know on twitter: [@haroenv](https://twitter.com/haroenv).

## License

Apache 2.0
