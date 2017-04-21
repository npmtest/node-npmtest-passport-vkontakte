# npmtest-passport-vkontakte

#### basic test coverage for  passport-vkontakte (v0.3.2)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-vkontakte.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-vkontakte) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-vkontakte.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-vkontakte)

#### VK.com authentication strategy for Passport.

[![NPM](https://nodei.co/npm/passport-vkontakte.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-vkontakte)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-vkontakte/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-vkontakte/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-vkontakte/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-vkontakte/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-vkontakte/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-vkontakte/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-vkontakte/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-vkontakte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-vkontakte/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-vkontakte/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "passport-vkontakte",
    "version": "0.3.2",
    "description": "VK.com authentication strategy for Passport.",
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "contributors": [
        {
            "name": "Stepan Stolyarov"
        }
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/stevebest/passport-vkontakte.git"
    },
    "bugs": {
        "url": "http://github.com/stevebest/passport-vkontakte/issues"
    },
    "main": "./lib/passport-vkontakte",
    "dependencies": {
        "pkginfo": "0.2.x",
        "passport-oauth2": "1.3.x"
    },
    "devDependencies": {
        "vows": "0.7.x"
    },
    "scripts": {
        "test": "NODE_PATH=lib 'npm bin'/vows test/*-test.js"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "keywords": [
        "passport",
        "vkontakte",
        "vk",
        "вконтакте",
        "auth",
        "authn",
        "authentication",
        "identity"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
