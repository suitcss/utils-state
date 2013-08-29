# SUIT utilities: state

[![Build Status](https://secure.travis-ci.org/suitcss/utils-state.png?branch=master)](http://travis-ci.org/suitcss/utils-state)

A SUIT collection of utility classes for low-level, global CSS states.

Read more about [SUIT's design principles](https://github.com/suitcss/suit/).

## Installation

* [Bower](http://bower.io/): `bower install --save suit-utils-state`
* [Component(1)](http://component.io/): `component install suitcss/utils-state`
* Download: [zip](https://github.com/suitcss/utils-state/zipball/master)
* Git: `git clone https://github.com/suitcss/utils-state.git`

## Available classes

* `u-isActionable` - Style with a `pointer` cursor to indicate an element will trigger an action.
* `u-isDisabled` - Style with a `default` cursor to indicate no associated action.
* `u-isDraggable` - Style with a `move` cursor to indicate an element can be dragged.
* `u-isHidden` - Completely remove an element from the flow and screen readers.
* `u-isHiddenVisually` - Completely remove an element from the flow but leave available to screen readers.
* `u-isVisible` - Make an element visible.
* `u-isInvisible` - Hide an element without affecting flow

## Usage

Please refer to the README for [SUIT utils](https://github.com/suitcss/utils/)

## Testing

Install [Node](http://nodejs.org) (comes with npm).

From the repo root, install the project's development dependencies:

```
npm install
```

To run the CSS Lint tests:

```
npm test
```

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+
