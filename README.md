# npmtest-jquery-form-validator

#### basic test coverage for  [jquery-form-validator (v2.3.60)](http://formvalidator.net/)  [![npm package](https://img.shields.io/npm/v/npmtest-jquery-form-validator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jquery-form-validator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jquery-form-validator.svg)](https://travis-ci.org/npmtest/node-npmtest-jquery-form-validator)

#### With this feature rich jQuery plugin it becomes easy to validate user input while keeping your HTML markup clean from javascript code. Even though this plugin has a wide range of validation functions it's designed to require as little bandwidth as possible. This is achieved by grouping together validation functions in "modules", making it possible for the programmer to load only those functions that's needed to validate a particular form.

[![NPM](https://nodei.co/npm/jquery-form-validator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jquery-form-validator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jquery-form-validator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jquery-form-validator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jquery-form-validator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jquery-form-validator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jquery-form-validator/build/test-report.html](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jquery-form-validator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jquery-form-validator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jquery-form-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jquery-form-validator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jquery-form-validator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jquery-form-validator",
    "description": "With this feature rich jQuery plugin it becomes easy to validate user input while keeping your HTML markup clean from javascript code. Even though this plugin has a wide range of validation functions it's designed to require as little bandwidth as possible. This is achieved by grouping together validation functions in \"modules\", making it possible for the programmer to load only those functions that's needed to validate a particular form.",
    "version": "2.3.60",
    "main": "./form-validator/jquery.form-validator.min.js",
    "keywords": [
        "form",
        "validator",
        "jquery"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/victorjonsson/jQuery-Form-Validator.git"
    },
    "bugs": {
        "url": "https://github.com/victorjonsson/jQuery-Form-Validator/issues"
    },
    "author": {
        "name": "Victor Jonsson",
        "url": "http://victorjonsson.se"
    },
    "homepage": "http://formvalidator.net/",
    "license": "MIT",
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-concat": "^0.5.1",
        "grunt-contrib-connect": "^0.11.2",
        "grunt-contrib-copy": "~1.0.0",
        "grunt-contrib-cssmin": "~0.14.0",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-qunit": "^0.7.0",
        "grunt-contrib-uglify": "~0.11.1",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-umd": "~2.4.0",
        "numeral": "~1.5.3",
        "qunitjs": "^1.20.0"
    },
    "dependencies": {
        "jquery": ">1.8.0"
    },
    "scripts": {
        "prepublish": "grunt prepublish",
        "test": "grunt test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
