# npmtest-bower-update

#### basic test coverage for  [bower-update (v0.2.0)](https://github.com/sapegin/bower-update)  [![npm package](https://img.shields.io/npm/v/npmtest-bower-update.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bower-update) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bower-update.svg)](https://travis-ci.org/npmtest/node-npmtest-bower-update)

#### Updates Bower components to the really latest versions.

[![NPM](https://nodei.co/npm/bower-update.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bower-update)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bower-update/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bower-update/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bower-update/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bower-update/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bower-update/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bower-update/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bower-update/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bower-update/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bower-update/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bower-update/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bower-update/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bower-update/build/test-report.html](https://npmtest.github.io/node-npmtest-bower-update/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bower-update/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bower-update/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bower-update/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bower-update/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bower-update/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bower-update/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bower-update/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bower-update/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Artem Sapegin",
        "url": "http://sapegin.me/"
    },
    "bin": {
        "bower-update": "bin/bower-update"
    },
    "bugs": {
        "url": "https://github.com/sapegin/bower-update/issues"
    },
    "dependencies": {
        "async": "~0.9.0",
        "bower": "~1.4.0",
        "chalk": "~1.0.0",
        "lodash": "~3.6.0",
        "nomnom": "~1.8.1",
        "readline-sync": "~0.8.0"
    },
    "deprecated": "Please use npm-check-updates",
    "description": "Updates Bower components to the really latest versions.",
    "devDependencies": {
        "chai": "~2.2.0",
        "coffee-script": "~1.9.1",
        "jscs": "~1.12.0",
        "jshint": "~2.6.3",
        "mocha": "~2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "410ded81975a5297d33315bd8dbec0aeb8a585b8",
        "tarball": "https://registry.npmjs.org/bower-update/-/bower-update-0.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "1452536680c15f0d9ba453c11329b3ca0bd8e234",
    "homepage": "https://github.com/sapegin/bower-update",
    "keywords": [
        "bower"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/sapegin/bower-update/blob/master/License.md"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "sapegin"
        }
    ],
    "name": "bower-update",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/sapegin/bower-update.git"
    },
    "scripts": {
        "jscs": "jscs index.js",
        "jshint": "jshint index.js",
        "mocha": "mocha --timeout 30000 --reporter spec --compilers coffee:coffee-script/register",
        "prepare": "cd test && rm -f bower.json && cp src/bower.json . && bower install",
        "test": "npm run jshint && npm run jscs && npm run prepare && npm run mocha"
    },
    "version": "0.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
