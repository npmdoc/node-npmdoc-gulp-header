# npmdoc-gulp-header

#### basic api documentation for  [gulp-header (v1.8.8)](https://github.com/tracker1/gulp-header#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-header.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-header) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-header.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-header)

#### Gulp extension to add header to file(s) in the pipeline.

[![NPM](https://nodei.co/npm/gulp-header.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-header)

- [https://npmdoc.github.io/node-npmdoc-gulp-header/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-header/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-header/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-header/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-header/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-header/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael J. Ryan",
        "url": "http://github.com/tracker1"
    },
    "bugs": {
        "url": "https://github.com/tracker1/gulp-header/issues"
    },
    "contributors": [
        {
            "name": "GoDaddy.com",
            "url": "http://github.com/godaddy"
        },
        {
            "name": "Douglas Duteil",
            "url": "http://github.com/douglasduteil"
        }
    ],
    "dependencies": {
        "concat-with-sourcemaps": "*",
        "gulp-util": "*",
        "object-assign": "*",
        "through2": "^2.0.0"
    },
    "description": "Gulp extension to add header to file(s) in the pipeline.",
    "devDependencies": {
        "event-stream": "^3.1.7",
        "gulp": "^3.9.0",
        "mocha": "*",
        "should": "*",
        "vinyl": "*"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "4509c64677aab56b5ee8e4669a79b1655933a49e",
        "tarball": "https://registry.npmjs.org/gulp-header/-/gulp-header-1.8.8.tgz"
    },
    "gitHead": "4d219649ba55069fe742195341fa3b71ae65976f",
    "homepage": "https://github.com/tracker1/gulp-header#readme",
    "https-proxy": null,
    "keywords": [
        "header",
        "gulpplugin",
        "eventstream"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "tracker1"
        }
    ],
    "name": "gulp-header",
    "optionalDependencies": {},
    "proxy": null,
    "repository": {
        "type": "git",
        "url": "git://github.com/tracker1/gulp-header.git"
    },
    "scripts": {
        "publish-major": "npm version major && git push origin master && git push --tags",
        "publish-minor": "npm version minor && git push origin master && git push --tags",
        "publish-patch": "npm version patch && git push origin master && git push --tags",
        "test": "mocha --reporter spec"
    },
    "version": "1.8.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
