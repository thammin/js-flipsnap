# Evil fork from flipsnap.js

[![Build Status](https://travis-ci.org/hokaccha/js-flipsnap.png?branch=master)](https://travis-ci.org/hokaccha/js-flipsnap)
[![Coverage Status](https://coveralls.io/repos/hokaccha/js-flipsnap/badge.png?branch=master)](https://coveralls.io/r/hokaccha/js-flipsnap?branch=master)

flipsnap.js is snap scroll for touch device.

> but this fork add an evil option that allow you to disable the snappable behavior. :smiling_imp:

http://hokaccha.github.com/js-flipsnap/

## Usage

```sh
npm install thammin/js-flipsnap#master
```

```js
var flipsnap = Flipsnap('#foo', { 
  disableSnap: true
});
```

## Why

This is useful when you have multiple small item within viewport and snappable behavior would make the scrolling a little unsmoothly. This option will release you from the limitation but also against the original purpose of `flipsnap.js`. :smiling_imp:

## License 

MIT

Original work Copyright (c) 2011 PixelGrid, Inc.

Modified work Copyright 2017 Paul Young <thammin@live.co.uk> 
