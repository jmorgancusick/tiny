# tiny

![npm (scoped)](https://img.shields.io/npm/v/@jmorgancusick/tiny)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@jmorgancusick/tiny)

A small package that removes spaces from a string.

Built to test AWS CodeArtifact.

# Install

~~~
npm install @jmorgancusick/tiny
~~~

# Usage

~~~
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
~~~
