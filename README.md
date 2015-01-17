# component-gauge  [![Build Status](https://travis-ci.org/dfcreative/component-gauge.svg?branch=master)](https://travis-ci.org/dfcreative/component-gauge) [![Code Climate](https://codeclimate.com/github/dfcreative/component-gauge/badges/gpa.svg)](https://codeclimate.com/github/dfcreative/component-gauge) ![size](https://img.shields.io/badge/size-1.35kb-brightgreen.svg) <a href="UNLICENSE"><img src="http://upload.wikimedia.org/wikipedia/commons/6/62/PD-icon.svg" width="20"/></a>

A simple circular gauge component.

[image]

[demo]

## Installation

`$ npm install component-gauge`

## Example

```js
var Gauge = require('component-gauge');
var gauge = new Gauge;
gauge.el.appendTo('body');
```


# API

### new Gauge(options)

Create a new Gauge component.

### Gauge.prototype.update()

Update gauge rings & marks position.


[![NPM](https://nodei.co/npm/component-gauge.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/component-gauge/)