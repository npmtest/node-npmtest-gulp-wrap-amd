# npmtest-gulp-wrap-amd

#### basic test coverage for  [gulp-wrap-amd (v0.5.0)](https://github.com/phated/gulp-wrap-amd)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-wrap-amd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-wrap-amd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-wrap-amd.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-wrap-amd)

#### Wrap files with an AMD wrapper

[![NPM](https://nodei.co/npm/gulp-wrap-amd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-wrap-amd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-wrap-amd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-wrap-amd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-wrap-amd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-wrap-amd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-wrap-amd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-wrap-amd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-wrap-amd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Blaine Bublitz"
    },
    "bugs": {
        "url": "https://github.com/phated/gulp-wrap-amd/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.4",
        "lodash": "^3.5.0",
        "through2": "^0.6.3"
    },
    "description": "Wrap files with an AMD wrapper",
    "devDependencies": {
        "gulp": "^3.8.11",
        "gulp-jshint": "^1.9.4",
        "lodash-cli": "^3.5.0",
        "tap": "^0.7.1"
    },
    "directories": {},
    "dist": {
        "shasum": "ea7bb2d969b6b2662a57f3489eecc7ca3f66e459",
        "tarball": "https://registry.npmjs.org/gulp-wrap-amd/-/gulp-wrap-amd-0.5.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "b361e33e4a72a64c5c47c4e0d1e8a15eb480cb63",
    "homepage": "https://github.com/phated/gulp-wrap-amd",
    "keywords": [
        "gulpplugin",
        "amd",
        "wrap"
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "phated"
        }
    ],
    "name": "gulp-wrap-amd",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/phated/gulp-wrap-amd.git"
    },
    "scripts": {
        "compile": "lodash template=./templates/*.jst exports=node -o template.js -d",
        "test": "gulp jshint && tap ./test/*.js"
    },
    "version": "0.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
