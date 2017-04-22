# npmtest-gulp-fontgen

#### basic test coverage for  [gulp-fontgen (v0.2.5)](https://github.com/agentk/gulp-fontgen)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-fontgen.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-fontgen) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-fontgen.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-fontgen)

#### Generator of browser fonts and css from ttf or otf files

[![NPM](https://nodei.co/npm/gulp-fontgen.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-fontgen)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-fontgen/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-fontgen/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-fontgen/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-fontgen/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-fontgen/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-fontgen/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-fontgen/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-fontgen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-fontgen/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-fontgen/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-fontgen",
    "description": "Generator of browser fonts and css from ttf or otf files",
    "version": "0.2.5",
    "homepage": "https://github.com/agentk/gulp-fontgen",
    "author": {
        "name": "Karl Bowden",
        "url": "http://karlbowden.com/"
    },
    "contributors": [
        {
            "name": "Julian Xhokaxhiu",
            "url": "http://julianxhokaxhiu.com"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/agentk/gulp-fontgen.git"
    },
    "bugs": {
        "url": "https://github.com/agentk/gulp-fontgen/issues"
    },
    "license": "Apache-2.0",
    "engines": {
        "node": ">= 0.12.0"
    },
    "scripts": {
        "lint": "eslint 'src/**/*.js'",
        "pretest": "npm run lint",
        "build": "babel src --out-dir lib",
        "prepublish": "npm run build",
        "test": "babel-node spec/es6.js && node spec/es5.js"
    },
    "main": "index.js",
    "keywords": [
        "gulpplugin",
        "font-face",
        "fontface",
        "font",
        "face",
        "web-fonts",
        "webfonts",
        "web",
        "ttf",
        "otf",
        "svg",
        "eot",
        "css"
    ],
    "dependencies": {
        "fontfacegen": "^0.2.1",
        "gulp-util": "^3.0.7",
        "through2": "^2.0.1"
    },
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-preset-es2015": "^6.9.0",
        "eslint": "^2.13.1",
        "eslint-config-airbnb-base": "^3.0.1",
        "eslint-plugin-import": "^1.9.2",
        "gulp": "^3.9.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
