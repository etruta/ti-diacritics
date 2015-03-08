# Titanium diacritics 

[![Available on gitTio](https://img.shields.io/badge/available_on-gitTio-00B4CC.svg?style=flat-square)](http://gitt.io/component/ti-diacritics)

Remove diacritics from strings.

Useful when implementing some kind of search or filter functionality.


## Install

Install using [gittio](http://gitt.io/)

~~~
$ gittio install diacritics
~~~


## Usage

~~~
var removeDiacritics = require('diacritics').remove;
Ti.API.log(removeDiacritics("Iлｔèｒｎåｔïｏｎɑｌíƶａｔï߀ԉ"));
// prints "Internationalizati0n"
~~~


## Credits

* [@andrewrk](https://github.com/andrewrk/node-diacritics) for create the original node module