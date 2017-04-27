# npmtest-html-webpack-plugin

#### basic test coverage for  [html-webpack-plugin (v2.28.0)](https://github.com/ampedandwired/html-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-html-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-html-webpack-plugin)

#### Simplifies creation of HTML files to serve your webpack bundles

[![NPM](https://nodei.co/npm/html-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-html-webpack-plugin/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charles Blaxland",
        "url": "https://github.com/ampedandwired"
    },
    "bugs": {
        "url": "https://github.com/ampedandwired/html-webpack-plugin/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.7",
        "html-minifier": "^3.2.3",
        "loader-utils": "^0.2.16",
        "lodash": "^4.17.3",
        "pretty-error": "^2.0.2",
        "toposort": "^1.0.0"
    },
    "description": "Simplifies creation of HTML files to serve your webpack bundles",
    "devDependencies": {
        "appcache-webpack-plugin": "^1.3.0",
        "css-loader": "^0.26.1",
        "dir-compare": "1.3.0",
        "es6-promise": "^4.0.5",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.9.0",
        "html-loader": "^0.4.4",
        "jade": "^1.11.0",
        "jade-loader": "^0.8.0",
        "jasmine": "^2.5.2",
        "rimraf": "^2.5.4",
        "semistandard": "8.0.0",
        "style-loader": "^0.13.1",
        "underscore-template-loader": "^0.7.3",
        "url-loader": "^0.5.7",
        "webpack": "^1.14.0",
        "webpack-recompilation-simulator": "^1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2e7863b57e5fd48fe263303e2ffc934c3064d009",
        "tarball": "https://registry.npmjs.org/html-webpack-plugin/-/html-webpack-plugin-2.28.0.tgz"
    },
    "files": [
        "index.js",
        "default_index.ejs",
        "lib/"
    ],
    "gitHead": "9bdb6189ea630a634a84aabc81a9bbe8c47bf92b",
    "homepage": "https://github.com/ampedandwired/html-webpack-plugin",
    "keywords": [
        "webpack",
        "plugin",
        "html",
        "html-webpack-plugin"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ampedandwired"
        },
        {
            "name": "jantimon"
        }
    ],
    "name": "html-webpack-plugin",
    "optionalDependencies": {},
    "peerDependencies": {
        "webpack": "1 || ^2 || ^2.1.0-beta || ^2.2.0-rc"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ampedandwired/html-webpack-plugin.git"
    },
    "scripts": {
        "build-examples": "node examples/build-examples.js",
        "prepublish": "npm run test",
        "pretest": "semistandard",
        "test": "jasmine"
    },
    "semistandard": {
        "ignore": [
            "examples/*/dist/**/*.*"
        ]
    },
    "version": "2.28.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
