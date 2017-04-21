# npmtest-grunt-injector

#### basic test coverage for  [grunt-injector (v1.1.0)](https://github.com/klei/grunt-injector)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-injector.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-injector) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-injector.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-injector)

#### Inject references to files into other files (think scripts and stylesheets into an html file)

[![NPM](https://nodei.co/npm/grunt-injector.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-injector)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-injector/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-injector/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-injector/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-injector/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-injector/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-injector/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-injector/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-injector/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-injector/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-injector/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-injector/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-injector/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-injector/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-injector/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-injector/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-injector/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-injector/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-injector/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-injector",
    "description": "Inject references to files into other files (think scripts and stylesheets into an html file)",
    "version": "1.1.0",
    "homepage": "https://github.com/klei/grunt-injector",
    "author": {
        "name": "Joakim Carlstein",
        "url": "http://joakim.beng.se"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/klei/grunt-injector.git"
    },
    "bugs": {
        "url": "https://github.com/klei/grunt-injector/issues"
    },
    "license": "MIT",
    "main": "Gruntfile.js",
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "grunt test"
    },
    "devDependencies": {
        "grunt": "~1.0.0",
        "grunt-cli": "~1.2.0",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-nodeunit": "~1.0.0"
    },
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "keywords": [
        "gruntplugin",
        "inject",
        "stylesheets",
        "scripts",
        "index",
        "bower"
    ],
    "dependencies": {
        "wiredep": "~4.0.0",
        "lodash": "~4.15.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
