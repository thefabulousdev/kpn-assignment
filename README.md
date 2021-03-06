# KPN Assignment

[![Build Status](https://travis-ci.org/thefabulousdev/kpn-assignment.svg?branch=master)](https://travis-ci.org/thefabulousdev/kpn-assignment)[![Code Climate](https://codeclimate.com/github/thefabulousdev/kpn-assignment/badges/gpa.svg)](https://codeclimate.com/github/thefabulousdev/kpn-assignment)

Skills assessment assignment for KPN

### Requirements

#### [Install node](https://nodejs.org/en/download/)

#### Install gulp and bower
``` sh
npm install gulp bower -g
```

#### Install dependencies
``` sh
npm install
bower install
```

### Use Gulp tasks

* `gulp` or `gulp build` to build an optimized version of the application in `/dist`
* `gulp serve` to launch a browser sync server on the source files
* `gulp serve:dist` to launch a server on the optimized application
* `gulp test` to launch the unit tests with Karma
* `gulp test:auto` to launch the unit tests with Karma in watch mode

### Remarks

 - On the assignment description it was specified that a product has
   subscriptions and each subscription has a device price, but if a
   given product is as given an "Apple iPhone 6s 64GB Zilver" wouldn't
   this be an constant value across its subscriptions?

### Author
Joel Hernandez

