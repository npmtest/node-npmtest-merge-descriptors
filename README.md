# npmtest-merge-descriptors

#### basic test coverage for  [merge-descriptors (v1.0.1)](https://github.com/component/merge-descriptors)  [![npm package](https://img.shields.io/npm/v/npmtest-merge-descriptors.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-merge-descriptors) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-merge-descriptors.svg)](https://travis-ci.org/npmtest/node-npmtest-merge-descriptors)

#### Merge objects using descriptors

[![NPM](https://nodei.co/npm/merge-descriptors.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/merge-descriptors)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-merge-descriptors/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-merge-descriptors/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-merge-descriptors/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-merge-descriptors/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-merge-descriptors/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-merge-descriptors/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-merge-descriptors/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-merge-descriptors/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-merge-descriptors/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-merge-descriptors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-merge-descriptors/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-merge-descriptors/build/test-report.html](https://npmtest.github.io/node-npmtest-merge-descriptors/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-merge-descriptors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-merge-descriptors/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-merge-descriptors/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-merge-descriptors/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-merge-descriptors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-merge-descriptors/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-merge-descriptors/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-merge-descriptors/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/component/merge-descriptors/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Mike Grabowski"
        }
    ],
    "dependencies": {},
    "description": "Merge objects using descriptors",
    "devDependencies": {
        "istanbul": "0.4.1",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "b00aaa556dd8b44568150ec9d1b953f3f90cbb61",
        "tarball": "https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "f26c49c3b423b0b2ac31f6e32a84e1632f2d7ac2",
    "homepage": "https://github.com/component/merge-descriptors",
    "license": "MIT",
    "maintainers": [
        {
            "name": "anthonyshort"
        },
        {
            "name": "clintwood"
        },
        {
            "name": "dfcreative"
        },
        {
            "name": "dominicbarnes"
        },
        {
            "name": "dougwilson"
        },
        {
            "name": "ianstormtaylor"
        },
        {
            "name": "jonathanong"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "mattmueller"
        },
        {
            "name": "queckezz"
        },
        {
            "name": "stephenmathieson"
        },
        {
            "name": "thehydroimpulse"
        },
        {
            "name": "timaschew"
        },
        {
            "name": "timoxley"
        },
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "tootallnate"
        },
        {
            "name": "trevorgerhardt"
        },
        {
            "name": "yields"
        }
    ],
    "name": "merge-descriptors",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/component/merge-descriptors.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/"
    },
    "version": "1.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
