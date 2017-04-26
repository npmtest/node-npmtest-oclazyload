# npmtest-oclazyload

#### basic test coverage for  [oclazyload (v1.1.0)](https://github.com/ocombe/ocLazyLoad)  [![npm package](https://img.shields.io/npm/v/npmtest-oclazyload.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-oclazyload) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-oclazyload.svg)](https://travis-ci.org/npmtest/node-npmtest-oclazyload)

#### Load modules on demand (lazy load) with angularJS

[![NPM](https://nodei.co/npm/oclazyload.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/oclazyload)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-oclazyload/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-oclazyload/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-oclazyload/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-oclazyload/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-oclazyload/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-oclazyload/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-oclazyload/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-oclazyload/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-oclazyload/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-oclazyload/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-oclazyload/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-oclazyload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-oclazyload/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-oclazyload/build/test-report.html](https://npmtest.github.io/node-npmtest-oclazyload/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-oclazyload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-oclazyload/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-oclazyload/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-oclazyload/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-oclazyload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-oclazyload/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-oclazyload/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-oclazyload/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Olivier Combe"
    },
    "bugs": {
        "url": "https://github.com/ocombe/ocLazyLoad/issues"
    },
    "dependencies": {},
    "description": "Load modules on demand (lazy load) with angularJS",
    "devDependencies": {
        "bower": "~1.4.1",
        "gulp": "~3.9.0",
        "gulp-babel": "~5.1.0",
        "gulp-clean": "~0.3.1",
        "gulp-concat": "~2.5.2",
        "gulp-exec": "~2.1.1",
        "gulp-header": "~1.2.2",
        "gulp-json-editor": "~2.2.1",
        "gulp-ng-annotate": "~1.0.0",
        "gulp-prompt": "~0.1.2",
        "gulp-rename": "~1.2.2",
        "gulp-uglify": "~1.2.0",
        "jasmine-core": "~2.3.4",
        "karma": "~0.12.35",
        "karma-babel-preprocessor": "~5.2.1",
        "karma-chrome-launcher": "~0.1.12",
        "karma-cli": "~0.0.4",
        "karma-coverage": "~0.3.1",
        "karma-firefox-launcher": "~0.1.6",
        "karma-jasmine": "~0.3.5",
        "qq": "~0.3.5",
        "requirejs": "~2.1.18",
        "run-sequence": "~1.1.0",
        "semver": "~4.3.6",
        "streamqueue": "~0.1.3"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "a9807322f190820a81c022f2ef1701d036d83e87",
        "tarball": "https://registry.npmjs.org/oclazyload/-/oclazyload-1.1.0.tgz"
    },
    "gitHead": "c282f8f47736c195a4079024f62f3c9e16420619",
    "homepage": "https://github.com/ocombe/ocLazyLoad",
    "keywords": [
        "lazy load",
        "lazy-load",
        "load on demand",
        "module",
        "angular",
        "angularJS"
    ],
    "license": "MIT",
    "main": "dist/ocLazyLoad.js",
    "maintainers": [
        {
            "name": "ocombe"
        }
    ],
    "name": "oclazyload",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ocombe/ocLazyLoad.git"
    },
    "scripts": {
        "bower": "bower install",
        "build": "gulp build-minify",
        "test": "karma start karma.conf.js",
        "test-dev": "karma start karma.conf.js --single-run=false"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
