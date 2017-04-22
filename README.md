# npmtest-fontmin

#### basic test coverage for  [fontmin (v0.9.6)](https://github.com/ecomfe/fontmin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-fontmin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fontmin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fontmin.svg)](https://travis-ci.org/npmtest/node-npmtest-fontmin)

#### Minify font seamlessly, font subsetter, webfont (eot, woff, svg) converter.

[![NPM](https://nodei.co/npm/fontmin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fontmin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fontmin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fontmin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fontmin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fontmin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fontmin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fontmin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fontmin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fontmin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fontmin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fontmin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fontmin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fontmin/build/test-report.html](https://npmtest.github.io/node-npmtest-fontmin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fontmin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fontmin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fontmin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fontmin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fontmin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fontmin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fontmin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fontmin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "junmer"
    },
    "bin": {
        "fontmin": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/ecomfe/fontmin/issues"
    },
    "dependencies": {
        "b3b": "0.0.1",
        "buffer-to-vinyl": "^1.0.0",
        "concat-stream": "^1.4.6",
        "fonteditor-core": "^0.0.21",
        "get-stdin": "^5.0.1",
        "is-otf": "^0.1.2",
        "is-svg": "^1.1.1",
        "is-ttf": "^0.2.2",
        "lodash": "^4.11.2",
        "meow": "^3.0.0",
        "pako": "^1.0.1",
        "replace-ext": "0.0.1",
        "stream-combiner": "^0.2.1",
        "through2": "2.0.1",
        "vinyl-fs": "2.4.3"
    },
    "description": "Minify font seamlessly, font subsetter, webfont (eot, woff, svg) converter.",
    "devDependencies": {
        "chai": "^3.5.0",
        "gulp-clean": "^0.3.1",
        "is-eot": "^1.0.0",
        "is-woff": "^1.0.1",
        "istanbul": "^0.4.3",
        "mocha": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1907967ee30d795a46b74119fc9295be5ba486ec",
        "tarball": "https://registry.npmjs.org/fontmin/-/fontmin-0.9.6.tgz"
    },
    "gitHead": "8f579ffffdfeb7a34ee1c23e8f873c9e49c6d7b9",
    "homepage": "https://github.com/ecomfe/fontmin#readme",
    "keywords": [
        "font",
        "webfont",
        "icon",
        "iconfont",
        "font-face",
        "compress",
        "minify",
        "font-cli",
        "otf",
        "ttf",
        "woff",
        "eot",
        "svg",
        "ttf2eot",
        "ttf2woff",
        "ttf2svg",
        "svg2ttf",
        "css",
        "base64"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "junmer"
        },
        {
            "name": "ecomfe"
        }
    ],
    "name": "fontmin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ecomfe/fontmin.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter spec --check-leaks test/",
        "test": "mocha"
    },
    "version": "0.9.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
