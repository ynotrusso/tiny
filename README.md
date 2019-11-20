# Tiny

Removes all spaces from a string

## Install

```
$ npm install @ynotrusso/tiny
```

## Usage

```js
const tiny = require("@ynotrusso/tiny");

tiny("So much space!");
//> "Somuchspace!"

tiny(123);
//> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
