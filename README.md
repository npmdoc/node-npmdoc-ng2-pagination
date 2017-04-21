# npmdoc-ng2-pagination

#### api documentation for  ng2-pagination (v2.0.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-ng2-pagination.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ng2-pagination) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ng2-pagination.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ng2-pagination)

#### Pagination for Angular

[![NPM](https://nodei.co/npm/ng2-pagination.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng2-pagination)

- [https://npmdoc.github.io/node-npmdoc-ng2-pagination/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng2-pagination/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng2-pagination/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng2-pagination/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ng2-pagination/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ng2-pagination/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ng2-pagination",
    "version": "2.0.1",
    "description": "Pagination for Angular",
    "main": "index.js",
    "scripts": {
        "build:system": "tsc -p config/tsconfig.system.json",
        "build:cjs": "ngc -p config/tsconfig.cjs.json",
        "build": "npm run build:cjs && npm run build:system",
        "test": "karma start config/karma.conf.js",
        "test:watch": "npm run test -- --auto-watch --no-single-run",
        "docs:watch": "webpack --config config/webpack.config.js --progress --colors --watch",
        "docs:dist": "webpack --config config/webpack.config.js --progress --colors -p --env.prod",
        "publish-lib": "npm run test && npm run build && npm run docs:dist"
    },
    "files": [
        "dist",
        "index.js",
        "index.d.ts"
    ],
    "keywords": [
        "angular",
        "angular2",
        "pagination"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/michaelbromley/ng2-pagination"
    },
    "bugs": {
        "url": "https://github.com/michaelbromley/ng2-pagination/issues"
    },
    "author": "Michael Bromley <michael@michaelbromley.co.uk>",
    "license": "MIT",
    "devDependencies": {
        "@angular/common": "^2.4.3",
        "@angular/compiler": "^2.4.3",
        "@angular/compiler-cli": "^2.4.3",
        "@angular/core": "^2.4.3",
        "@angular/forms": "^2.4.3",
        "@angular/platform-browser": "^2.4.3",
        "@angular/platform-browser-dynamic": "^2.4.3",
        "@angular/platform-server": "^2.4.3",
        "@angular/router": "3.4.3",
        "@ngtools/webpack": "1.1.4",
        "@types/es6-shim": "^0.31.32",
        "@types/jasmine": "2.5.41",
        "@types/node": "^6.0.45",
        "angular2-template-loader": "0.6.0",
        "bulma": "0.2.3",
        "core-js": "^2.4.0",
        "css-loader": "^0.23.1",
        "es6-promise": "^3.0.2",
        "es6-shim": "^0.35.0",
        "highlight.js": "^9.1.0",
        "html-loader": "^0.4.3",
        "jasmine-core": "^2.4.1",
        "json-loader": "^0.5.4",
        "karma": "1.2.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-jasmine": "1.0.2",
        "karma-mocha-reporter": "^2.2.0",
        "karma-phantomjs-launcher": "1.0.2",
        "karma-webpack": "^1.8.0",
        "marked": "^0.3.6",
        "node-sass": "^3.6.0",
        "phantomjs-prebuilt": "^2.1.7",
        "raw-loader": "^0.5.1",
        "reflect-metadata": "0.1.3",
        "rxjs": "^5.0.3",
        "sass-loader": "^3.1.2",
        "style-loader": "^0.13.1",
        "ts-loader": "^1.0.0",
        "typescript": "2.0.6",
        "webpack": "2.1.0-beta.25",
        "zone.js": "0.7.4"
    },
    "dependencies": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
