# npmdoc-redux-loop

#### api documentation for  [redux-loop (v2.2.2)](https://github.com/redux-loop/redux-loop)  [![npm package](https://img.shields.io/npm/v/npmdoc-redux-loop.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-redux-loop) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux-loop.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux-loop)

#### Sequence your effects naturally and purely by returning them from your reducers.

[![NPM](https://nodei.co/npm/redux-loop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-loop)

- [https://npmdoc.github.io/node-npmdoc-redux-loop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-loop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-loop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-loop/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redux-loop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redux-loop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Luke William Westby",
        "url": "https://twitter.com/luke_dot_js"
    },
    "bugs": {
        "url": "https://github.com/redux-loop/redux-loop/issues"
    },
    "contributors": [],
    "dependencies": {},
    "description": "Sequence your effects naturally and purely by returning them from your reducers.",
    "devDependencies": {
        "babel": "6.3.13",
        "babel-cli": "6.3.17",
        "babel-plugin-transform-es3-member-expression-literals": "6.3.13",
        "babel-plugin-transform-es3-property-literals": "6.3.13",
        "babel-plugin-transform-object-rest-spread": "6.3.13",
        "babel-polyfill": "6.7.2",
        "babel-preset-es2015": "6.3.13",
        "babel-register": "6.7.2",
        "immutable": "^3.7.6",
        "redux": "3.0.5",
        "rimraf": "2.4.4",
        "tape": "4.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "1df804487be0f79daf7eff065ad8301ce255fd4e",
        "tarball": "https://registry.npmjs.org/redux-loop/-/redux-loop-2.2.2.tgz"
    },
    "files": [
        "modules",
        "lib"
    ],
    "gitHead": "0da84e946e2b262f98c836ad310fcd0d80bee94d",
    "homepage": "https://github.com/redux-loop/redux-loop",
    "jsnext:main": "modules/index.js",
    "keywords": [
        "redux",
        "middleware",
        "effects",
        "side effects",
        "elm",
        "loop"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "lukewestby"
        },
        {
            "name": "ndreckshage"
        }
    ],
    "name": "redux-loop",
    "npmName": "redux-loop",
    "optionalDependencies": {},
    "peerDependencies": {
        "redux": "^3.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/redux-loop/redux-loop.git"
    },
    "scripts": {
        "build": "babel modules --out-dir lib",
        "clean": "rimraf lib",
        "prepublish": "npm run clean && npm run build",
        "test": "tape -r babel-polyfill -r babel-register './test/*.test.js'"
    },
    "tags": [
        "redux",
        "middleware",
        "effects",
        "side effects",
        "elm",
        "loop"
    ],
    "version": "2.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
