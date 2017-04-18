# npmdoc-vinyl

#### api documentation for  [vinyl (v2.0.2)](https://github.com/gulpjs/vinyl#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-vinyl.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-vinyl) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-vinyl.svg)](https://travis-ci.org/npmdoc/node-npmdoc-vinyl)

#### Virtual file format.

[![NPM](https://nodei.co/npm/vinyl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vinyl)

- [https://npmdoc.github.io/node-npmdoc-vinyl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vinyl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vinyl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vinyl/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-vinyl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-vinyl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gulp Team",
        "url": "http://gulpjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gulpjs/vinyl/issues"
    },
    "contributors": [
        {
            "name": "Eric Schoffstall"
        },
        {
            "name": "Blaine Bublitz"
        }
    ],
    "dependencies": {
        "clone": "^1.0.0",
        "clone-buffer": "^1.0.0",
        "clone-stats": "^1.0.0",
        "cloneable-readable": "^1.0.0",
        "is-stream": "^1.1.0",
        "remove-trailing-separator": "^1.0.1",
        "replace-ext": "^1.0.0"
    },
    "description": "Virtual file format.",
    "devDependencies": {
        "eslint": "^1.7.3",
        "eslint-config-gulp": "^2.0.0",
        "expect": "^1.20.2",
        "istanbul": "^0.4.3",
        "istanbul-coveralls": "^1.0.3",
        "jscs": "^2.3.5",
        "jscs-preset-gulp": "^1.0.0",
        "mississippi": "^1.2.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "0a3713d8d4e9221c58f10ca16c0116c9e25eda7c",
        "tarball": "https://registry.npmjs.org/vinyl/-/vinyl-2.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "LICENSE",
        "index.js",
        "lib"
    ],
    "gitHead": "e014ed1594f537ef469416610ab336d7b489630b",
    "homepage": "https://github.com/gulpjs/vinyl#readme",
    "keywords": [
        "virtual",
        "filesystem",
        "file",
        "directory",
        "stat",
        "path"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "contra"
        },
        {
            "name": "fractal"
        },
        {
            "name": "phated"
        }
    ],
    "name": "vinyl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gulpjs/vinyl.git"
    },
    "scripts": {
        "cover": "istanbul cover _mocha --report lcovonly",
        "coveralls": "npm run cover && istanbul-coveralls",
        "lint": "eslint . && jscs index.js lib/ test/",
        "pretest": "npm run lint",
        "test": "mocha --async-only"
    },
    "version": "2.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
