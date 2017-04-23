# npmdoc-doctoc

#### api documentation for  [doctoc (v1.3.0)](https://github.com/thlorenz/doctoc#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-doctoc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-doctoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-doctoc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-doctoc)

#### Generates TOC for markdown files of local git repo.

[![NPM](https://nodei.co/npm/doctoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/doctoc)

- [https://npmdoc.github.io/node-npmdoc-doctoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-doctoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-doctoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-doctoc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-doctoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-doctoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thorsten Lorenz",
        "url": "thlorenz.com"
    },
    "bin": {
        "doctoc": "doctoc.js"
    },
    "bugs": {
        "url": "https://github.com/thlorenz/doctoc/issues"
    },
    "dependencies": {
        "anchor-markdown-header": "^0.5.5",
        "htmlparser2": "~3.9.2",
        "markdown-to-ast": "~3.4.0",
        "minimist": "~1.2.0",
        "underscore": "~1.8.3",
        "update-section": "^0.3.0"
    },
    "description": "Generates TOC for markdown files of local git repo.",
    "devDependencies": {
        "tap": "~10.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7f0839851dd58c808a2cae55d9504e012d08ee30",
        "tarball": "https://registry.npmjs.org/doctoc/-/doctoc-1.3.0.tgz"
    },
    "engines": {
        "node": ">=0.4"
    },
    "gitHead": "b96694ff868962cb93054d3913ebd3bda8d26fda",
    "homepage": "https://github.com/thlorenz/doctoc#readme",
    "keywords": [
        "github",
        "markdown",
        "documentation",
        "readme",
        "parser",
        "bitbucket",
        "gitlab",
        "ghost"
    ],
    "license": "MIT",
    "main": "doctoc.js",
    "maintainers": [
        {
            "name": "thlorenz"
        }
    ],
    "name": "doctoc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/doctoc.git"
    },
    "scripts": {
        "test": "set -e; for t in test/*.js; do node $t; done"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
