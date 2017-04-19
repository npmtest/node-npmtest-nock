# npmtest-nock

#### basic test coverage for  [nock (v9.0.13)](https://github.com/node-nock/nock#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nock.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nock) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nock.svg)](https://travis-ci.org/npmtest/node-npmtest-nock)

#### HTTP Server mocking for Node.js

[![NPM](https://nodei.co/npm/nock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nock)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nock/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nock/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nock/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nock/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nock/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nock/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nock/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nock/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nock/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nock/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nock/build/test-report.html](https://npmtest.github.io/node-npmtest-nock/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nock/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nock/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pedro Teixeira"
    },
    "bugs": {
        "url": "http://github.com/node-nock/nock/issues"
    },
    "contributors": [
        {
            "name": "Bin Chang",
            "url": "https://github.com/BinChang"
        },
        {
            "name": "Roman Hotsiy",
            "url": "https://github.com/RomanGotsiy"
        },
        {
            "name": "Jeffrey Jagoda",
            "url": "https://github.com/jagoda"
        },
        {
            "name": "Hidenari Nozaki",
            "url": "https://github.com/ghiden"
        },
        {
            "name": "Ken Sheedlo",
            "url": "https://github.com/ksheedlo"
        },
        {
            "name": "Douglas Eggleton",
            "url": "https://github.com/douglaseggleton"
        },
        {
            "name": "José F. Romaniello",
            "url": "https://github.com/jfromaniello"
        },
        {
            "name": "Benjamin Urban",
            "url": "https://github.com/benurb"
        },
        {
            "name": "Justin",
            "url": "https://github.com/justincy"
        },
        {
            "name": "Brett Porter"
        },
        {
            "name": "Matt Olson"
        },
        {
            "name": "Rémy HUBSCHER"
        },
        {
            "name": "Roly Fentanes"
        },
        {
            "name": "Alexander Simmerl"
        },
        {
            "name": "Pedro Teixeira"
        },
        {
            "name": "Nuno Job"
        },
        {
            "name": "Ian Young"
        },
        {
            "name": "nilsbunger"
        },
        {
            "name": "bacchusrx"
        },
        {
            "name": "Fabiano França"
        },
        {
            "name": "Sascha Drews"
        },
        {
            "name": "Mike Swift"
        },
        {
            "name": "James Herdman"
        },
        {
            "name": "David Björklund"
        },
        {
            "name": "Andrew Kramolisch"
        },
        {
            "name": "Balazs Nagy"
        },
        {
            "name": "Brian J Brennan"
        },
        {
            "name": "Attila Incze"
        },
        {
            "name": "Mac Angell"
        },
        {
            "name": "Tom Hosford"
        },
        {
            "name": "Aurélien Thieriot"
        },
        {
            "name": "Alex Zylman"
        },
        {
            "name": "Celestino Gomes"
        },
        {
            "name": "David Rousselie"
        },
        {
            "name": "spenceralger"
        },
        {
            "name": "Ivan Erceg",
            "url": "https://github.com/ierceg"
        },
        {
            "name": "Keith Laban",
            "url": "https://github.com/kelaban"
        },
        {
            "name": "Rui Marinho",
            "url": "https://github.com/ruimarinho"
        },
        {
            "name": "David Pate",
            "url": "https://github.com/DavidTPate"
        },
        {
            "name": "Matt Oakes",
            "url": "https://github.com/matto1990"
        },
        {
            "name": "Ian Walker-Sperber",
            "url": "https://github.com/ianwsperber"
        }
    ],
    "dependencies": {
        "chai": ">=1.9.2 <4.0.0",
        "debug": "^2.2.0",
        "deep-equal": "^1.0.0",
        "json-stringify-safe": "^5.0.1",
        "lodash": "~4.17.2",
        "mkdirp": "^0.5.0",
        "propagate": "0.4.0",
        "qs": "^6.0.2"
    },
    "description": "HTTP Server mocking for Node.js",
    "devDependencies": {
        "async": "^2.1.1",
        "aws-sdk": "^2.0.15",
        "browserify": "^13.0.0",
        "changelog": "^1.0.7",
        "coveralls": "^2.11.2",
        "glob": "^7.1.1",
        "hyperquest": "^1.3.0",
        "isomorphic-fetch": "^2.2.0",
        "istanbul": "^0.4.2",
        "jshint": "^2.5.6",
        "markdown-toc": "^0.13.0",
        "needle": "^1.0.0",
        "node-static": "^0.7.7",
        "nyc": "^10.0.0",
        "pre-commit": "1.1.2",
        "request": "2.71.0",
        "request-promise": "^2.0.1",
        "restify": "^4.0.4",
        "restler": "3.4.0",
        "rimraf": "^2.3.2",
        "superagent": "^3.5.0",
        "tap": "^10.0.0",
        "zombie": "^5.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d0bc39ef43d3179981e22b2e8ea069f916c5781a",
        "tarball": "https://registry.npmjs.org/nock/-/nock-9.0.13.tgz"
    },
    "engines": [
        "node >= 4.0"
    ],
    "gitHead": "f26818796b2448d00f1cda2d8533afb7d73c4cd2",
    "homepage": "https://github.com/node-nock/nock#readme",
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "ianwsperber"
        },
        {
            "name": "ierceg"
        },
        {
            "name": "pgte"
        },
        {
            "name": "ruimarinho"
        },
        {
            "name": "svnlto"
        },
        {
            "name": "vrinek"
        }
    ],
    "name": "nock",
    "nyc": {
        "reporter": [
            "lcov",
            "text-summary"
        ],
        "exclude": [
            "tests/test_*.js"
        ]
    },
    "optionalDependencies": {},
    "pre-commit": [
        "jshint",
        "coverage"
    ],
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/node-nock/nock.git"
    },
    "scripts": {
        "changelog": "changelog nock all -m > CHANGELOG.md",
        "coverage": "nyc tap --harmony ./tests/test_*.js",
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "integration": "tap --harmony ./tests/versioned/*/*.tap.js",
        "jshint": "jshint lib/*.js",
        "preintegration": "./tests/bin/install_sub_deps versioned",
        "test": "npm run unit && npm run integration",
        "toc": "markdown-toc -i README.md",
        "unit": "tap --harmony ./tests/test_*.js"
    },
    "tags": [
        "Mock",
        "HTTP",
        "testing",
        "isolation"
    ],
    "version": "9.0.13"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
