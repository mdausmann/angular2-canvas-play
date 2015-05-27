Canvas written in Angular 2
===========================

The goal of this repo is to offer up a simple working example of a multi-component application in Angular2.

Based on https://github.com/pkozlowski-opensource/ng2-play

## Install

Clone this repo and execute in your favourite shell:

* `npm i -g gulp` to install gulp globally (if you don't have it installed already)
* `npm i` to install local npm dependencies

## Play

After completing installation type in your favourite shell:

* `gulp play` (or `npm start`) to start a "Hello World" app in a new browser window. App files are observed and will be re-transpiled on each change.

## Dependencies

* ES6 -> ES5 transpilation
    * [traceur](https://github.com/google/traceur-compiler): ES6 -> ES5 transpilation
* ES6 modules loading
    * [es6-module-loader](https://github.com/ModuleLoader/es6-module-loader): ES6 module loader polyfill
    * [systemjs](https://github.com/systemjs/systemjs): plugins for the ES6 module loader to handle different module formats - this is mostly needed to load module format generated by traceur

## Learning materials

### Zones / long stack-traces

* [original repo](https://github.com/angular/zone.js)
* [zones in Dart](https://www.dartlang.org/articles/zones/)
* [zones in node](http://strongloop.com/strongblog/comparing-node-js-promises-trycatch-zone-js-angular/)

### ES6 module loading

* [Practical Workflows for ES6 Modules, Fluent 2014](https://www.youtube.com/watch?v=0VUjM-jJf2U)
* [Guy Bedford: Package Management for ES6 Modules, JSConf2014](https://www.youtube.com/watch?v=szJjsduHBQQ)
* [Loader API specification](http://whatwg.github.io/loader/) 
