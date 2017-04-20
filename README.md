# npmtest-weexpack

#### basic test coverage for  weexpack (v0.4.0)  [![npm package](https://img.shields.io/npm/v/npmtest-weexpack.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-weexpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-weexpack.svg)](https://travis-ci.org/npmtest/node-npmtest-weexpack)

#### Weex pack tool

[![NPM](https://nodei.co/npm/weexpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/weexpack)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-weexpack/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-weexpack/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-weexpack/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-weexpack/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-weexpack/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-weexpack/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-weexpack/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-weexpack/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-weexpack/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-weexpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-weexpack/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-weexpack/build/test-report.html](https://npmtest.github.io/node-npmtest-weexpack/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-weexpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-weexpack/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-weexpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-weexpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-weexpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-weexpack/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-weexpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-weexpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "weexpack",
    "version": "0.4.0",
    "description": "Weex pack tool",
    "main": "index.js",
    "scripts": {
        "test": "mocha ./tests/*.test.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/weexteam/weex-pack.git"
    },
    "engines": {
        "node": ">=6"
    },
    "bin": {
        "weexpack": "./bin/weexpack"
    },
    "keywords": [
        "weex",
        "weexpack",
        "tool",
        "toolkit"
    ],
    "author": "",
    "contributors": [
        "Hanks <zhanghan.me@gmail.com>",
        "Fkysly <fkysly@gmail.com>",
        "VeHan <android_xiaowei@163.com>",
        "ankokuji <moritaka325@163.com>",
        "liujiescut <969343185@qq.com>",
        "shujiewz <rememberwz@gmail.com>",
        "Icemic <bingfeng.web@gmail.com>",
        "exolution <exolution@163.com>"
    ],
    "license": "Apache-2.0",
    "dependencies": {
        "aliasify": "^1.7.2",
        "ansi": "^0.3.1",
        "bplist-parser": "^0.1.0",
        "browserify": "13.1.0",
        "chalk": "^1.1.3",
        "commander": "^2.9.0",
        "compression": "^1.6.0",
        "cordova-fetch": "^1.0.1",
        "cordova-js": "4.2.0",
        "cordova-registry-mapper": "1.x",
        "cordova-serve": "^1.0.0",
        "dep-graph": "1.1.0",
        "dependency-ls": "^1.0.0",
        "elementtree": "0.1.6",
        "eslint": "^3.5.0",
        "express": "^4.13.3",
        "gauge": "^2.7.2",
        "generator-weex-plugin": "^0.1.23",
        "glob": "^5.0.3",
        "init-package-json": "^1.2.0",
        "inquirer": "^1.1.3",
        "insight": "~0.8.2",
        "ios-sim": "^5.0.12",
        "is-url": "^1.2.1",
        "merge": "^1.2.0",
        "minimatch": "^3.0.0",
        "mkdirp": "^0.5.1",
        "nopt": "^3.0.6",
        "npm": "^2.10.x",
        "opener": "^1.4.2",
        "osenv": "^0.1.3",
        "plist": "^1.2.0",
        "prompt": "^1.0.0",
        "properties-parser": "0.2.3",
        "q": "1.0.1",
        "recursive-copy": "^2.0.5",
        "request": "2.47.0",
        "semver": "^4.3.x",
        "shelljs": "^0.3.0",
        "tar": "^1.0.2",
        "underscore": "1.7.0",
        "unorm": "1.3.3",
        "update-notifier": "^0.5.0",
        "valid-identifier": "0.0.1",
        "weexpack-common": "^0.1.2",
        "weexpack-create": "^0.1.0",
        "weexpack-lib": "^0.1.0",
        "xcode": "^0.8.5",
        "yeoman-environment": "^1.6.3",
        "yeoman-generator": "^0.24.1"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^3.2.0"
    },
    "weexpack": "0.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
