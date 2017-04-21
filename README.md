# npmtest-kefir

#### basic test coverage for  [kefir (v3.7.1)](https://github.com/rpominov/kefir)  [![npm package](https://img.shields.io/npm/v/npmtest-kefir.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-kefir) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-kefir.svg)](https://travis-ci.org/npmtest/node-npmtest-kefir)

#### Reactive Programming library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory usage

[![NPM](https://nodei.co/npm/kefir.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kefir)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-kefir/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-kefir/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-kefir/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-kefir/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-kefir/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-kefir/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-kefir/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-kefir/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-kefir/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-kefir/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-kefir/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-kefir/build/test-report.html](https://npmtest.github.io/node-npmtest-kefir/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-kefir/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-kefir/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-kefir/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kefir/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kefir/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kefir/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-kefir/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-kefir/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "kefir",
    "version": "3.7.1",
    "description": "Reactive Programming library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory usage",
    "main": "dist/kefir.js",
    "scripts": {
        "test": "eslint . && grunt rollup:dev && jasmine-node --coffee --matchall test/specs && flow check",
        "test-only": "grunt rollup:dev && jasmine-node --coffee --matchall test/specs"
    },
    "keywords": [
        "frp",
        "bacon",
        "bacon.js",
        "kefir",
        "kefir.js",
        "functional",
        "reactive",
        "stream",
        "streams",
        "EventStream",
        "Rx",
        "RxJs",
        "Observable"
    ],
    "author": "Roman Pominov <rpominov@gmail.com>",
    "homepage": "https://github.com/rpominov/kefir",
    "repository": {
        "type": "git",
        "url": "http://github.com/rpominov/kefir.git"
    },
    "license": "MIT",
    "devDependencies": {
        "@reactivex/rxjs": "5.0.0-alpha.1",
        "babel-core": "6.10.4",
        "babel-preset-es2015": "6.9.0",
        "babel-preset-es2015-loose": "7.0.0",
        "babel-preset-es2015-loose-rollup": "7.0.0",
        "babelify": "7.3.0",
        "coffee-script": "1.10.0",
        "coffeeify": "1.1.0",
        "eslint": "2.2.0",
        "flow-bin": "^0.36.0",
        "grunt": "0.4.5",
        "grunt-bower-task": "0.4.0",
        "grunt-browserify": "4.0.1",
        "grunt-cli": "0.1.13",
        "grunt-contrib-clean": "0.6.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-jade": "0.15.0",
        "grunt-rollup": "0.7.1",
        "inquirer": "0.10.1",
        "jasmine-node": "1.14.5",
        "load-grunt-tasks": "3.3.0",
        "rollup": "0.33.0",
        "rollup-plugin-babel": "2.6.1",
        "rollup-plugin-commonjs": "3.1.0",
        "rollup-plugin-node-resolve": "1.7.1",
        "rollup-plugin-uglify": "1.0.1",
        "semver": "5.0.3",
        "shelljs": "0.5.3",
        "sinon": "1.17.1",
        "time-grunt": "1.2.1",
        "transducers-js": "0.4.174",
        "transducers.js": "0.3.2",
        "zen-observable": "0.3.0"
    },
    "dependencies": {
        "symbol-observable": "^1.0.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
