# npmtest-safe-regex

#### basic test coverage for  [safe-regex (v1.1.0)](https://github.com/substack/safe-regex)  [![npm package](https://img.shields.io/npm/v/npmtest-safe-regex.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-safe-regex) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-safe-regex.svg)](https://travis-ci.org/npmtest/node-npmtest-safe-regex)

#### detect possibly catastrophic, exponential-time regular expressions

[![NPM](https://nodei.co/npm/safe-regex.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/safe-regex)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-safe-regex/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-safe-regex/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-safe-regex/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-safe-regex/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-safe-regex/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-safe-regex/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-safe-regex/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-safe-regex/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-safe-regex/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-safe-regex/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-safe-regex/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-safe-regex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-safe-regex/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-safe-regex/build/test-report.html](https://npmtest.github.io/node-npmtest-safe-regex/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-safe-regex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-safe-regex/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-safe-regex/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-safe-regex/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-safe-regex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-safe-regex/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-safe-regex/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-safe-regex/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/safe-regex/issues"
    },
    "dependencies": {
        "ret": "~0.1.10"
    },
    "description": "detect possibly catastrophic, exponential-time regular expressions",
    "devDependencies": {
        "tape": "^3.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "40a3669f3b077d1e943d44629e157dd48023bf2e",
        "tarball": "https://registry.npmjs.org/safe-regex/-/safe-regex-1.1.0.tgz"
    },
    "gitHead": "d2570f31bd9d779515015917bb8297c753e46572",
    "homepage": "https://github.com/substack/safe-regex",
    "keywords": [
        "catastrophic",
        "exponential",
        "regex",
        "safe",
        "sandbox"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        }
    ],
    "name": "safe-regex",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/safe-regex.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8",
            "ie/9",
            "ie/10",
            "firefox/latest",
            "chrome/latest",
            "opera/latest",
            "safari/latest"
        ]
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
