# A demo app for using Redux with Polymer 2

This small demo application shows how the principles of [Redux](http://redux.js.org/) can be applied to building an app with [Polymer 2](https://www.polymer-project.org/). It uses the Redux implementation from the [polymer-redux](https://github.com/tur-nr/polymer-redux/tree/polymer-2) library (and therefore works well with the [Redux DevTools](https://github.com/zalmoxisus/redux-devtools-extension) Chrome extension).

The live version is deployed to the GitHub pages: [https://vlukashov.github.io/redux-polymer-gridpaint/](https://vlukashov.github.io/redux-polymer-gridpaint/).

This application is based off of [another Redux demo app](https://github.com/argelius/react-redux-timetravel).

## Installation
requires Node and NPM
```shell
$ git clone https://github.com/vlukashov/redux-polymer-gridpaint.git
$ cd redux-polymer-gridpaint
$ npm install
```

## Start
Starts a development server on [localhost:8081](http://localhost:8081)
```shell
$ npm start
```

## Running Tests

```
$ npm test
```

The application is set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to execute the test suite locally.
