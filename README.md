# React Calculator
A calculator built with React, Redux, Ramda and point free functional programming.

## Features
- Point-free functional programming with [Ramda](http://ramdajs.com/).
- Math expression evaluation based on [Math.js](http://mathjs.org/).
- Uses [Redux](redux.js.org) for validating pressed keys and calculating expressions while typing. Default keys for basic arithmetic calculations, but easy to customize the allowed keys (see [initialState.js](https://github.com/panayi/calculator/blob/master/src/initialState.js)).
- Theme switching based on Redux, a custom `<ThemeManager>` component and [Radium](https://github.com/FormidableLabs/radium).
- Based on [react-redux-starter-kit](https://github.com/davezuko/react-redux-starter-kit).

## Usage

```
git clone git@github.com:kenyoshida612/react-calculator.git
cd react-calculator
npm install
npm run dev
```

Go to [http://localhost:3000/](http://localhost:3000/)

## Tests
Watch for changes and re-run tests:

```
npm run test:dev
```

Run tests once and generate coverage report:

```
npm run test
```
