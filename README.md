# npmdoc-exectimer

#### api documentation for  [exectimer (v2.0.3)](https://github.com/alexandrusavin/exectimer)  [![npm package](https://img.shields.io/npm/v/npmdoc-exectimer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-exectimer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-exectimer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-exectimer)

#### Very simple module to calculate block execution time.

[![NPM](https://nodei.co/npm/exectimer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/exectimer)

- [https://npmdoc.github.io/node-npmdoc-exectimer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-exectimer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-exectimer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-exectimer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-exectimer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-exectimer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "exectimer",
    "version": "2.0.3",
    "description": "Very simple module to calculate block execution time.",
    "keywords": [
        "time",
        "timer",
        "profiler",
        "execution",
        "performance",
        "analysis",
        "benchmark"
    ],
    "homepage": "https://github.com/alexandrusavin/exectimer",
    "bugs": "https://github.com/alexandrusavin/exectimer/issues",
    "author": {
        "name": "Alexandru Savin"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/alexandrusavin/exectimer.git"
    },
    "main": "./index",
    "scripts": {
        "test": "./node_modules/.bin/mocha test/**/*.js",
        "jshint": "jshint --config .jshintrc --exclude node_modules *.js"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "devDependencies": {
        "async": "^1.5.0",
        "chai": "^3.4.1",
        "mocha": "^2.3.4",
        "should": "^7.1.1"
    },
    "dependencies": {
        "co": "^4.6.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
