# api documentation for  [phantomjs (v2.1.7)](https://github.com/Medium/phantomjs)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-phantomjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-phantomjs)
#### Headless WebKit with JS API

[![NPM](https://nodei.co/npm/phantomjs.png?downloads=true)](https://www.npmjs.com/package/phantomjs)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phantomjs/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-phantomjs_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phantomjs/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-phantomjs/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Pupius",
        "email": "dan@obvious.com",
        "url": "http://pupius.co.uk"
    },
    "bin": {
        "phantomjs": "./bin/phantomjs"
    },
    "bugs": {
        "url": "https://github.com/Medium/phantomjs/issues"
    },
    "dependencies": {
        "extract-zip": "~1.5.0",
        "fs-extra": "~0.26.4",
        "hasha": "^2.2.0",
        "kew": "~0.7.0",
        "progress": "~1.1.8",
        "request": "~2.67.0",
        "request-progress": "~2.0.1",
        "which": "~1.2.2"
    },
    "deprecated": "Package renamed to phantomjs-prebuilt. Please update 'phantomjs' package references to 'phantomjs-prebuilt'",
    "description": "Headless WebKit with JS API",
    "devDependencies": {
        "eslint": "1.10.3",
        "nodeunit": "0.9.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c6910f67935c37285b6114329fc2f27d5f3e3134",
        "tarball": "https://registry.npmjs.org/phantomjs/-/phantomjs-2.1.7.tgz"
    },
    "gitHead": "21e7232131b60f2573e110cf89d156a33e8f293c",
    "homepage": "https://github.com/Medium/phantomjs",
    "keywords": [
        "phantomjs",
        "headless",
        "webkit"
    ],
    "license": "Apache-2.0",
    "main": "lib/phantomjs",
    "maintainers": [
        {
            "name": "dpup",
            "email": "dan@pupi.us"
        },
        {
            "name": "nicks",
            "email": "nicholas.j.santos@gmail.com"
        },
        {
            "name": "medium",
            "email": "npm@medium.com"
        }
    ],
    "name": "phantomjs",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Medium/phantomjs.git"
    },
    "scripts": {
        "install": "node install.js",
        "test": "nodeunit --reporter=minimal test/tests.js && eslint install.js"
    },
    "version": "2.1.7"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module phantomjs](#apidoc.module.phantomjs)
1.  [function <span class="apidocSignatureSpan">phantomjs.</span>cleanPath (path)](#apidoc.element.phantomjs.cleanPath)
1.  string <span class="apidocSignatureSpan">phantomjs.</span>arch
1.  string <span class="apidocSignatureSpan">phantomjs.</span>path
1.  string <span class="apidocSignatureSpan">phantomjs.</span>platform
1.  string <span class="apidocSignatureSpan">phantomjs.</span>version



# <a name="apidoc.module.phantomjs"></a>[module phantomjs](#apidoc.module.phantomjs)

#### <a name="apidoc.element.phantomjs.cleanPath"></a>[function <span class="apidocSignatureSpan">phantomjs.</span>cleanPath (path)](#apidoc.element.phantomjs.cleanPath)
- description and source-code
```javascript
cleanPath = function (path) {
  return path
      .replace(/:[^:]*node_modules[^:]*/g, '')
      .replace(/(^|:)\.\/bin(\:|$)/g, ':')
      .replace(/^:+/, '')
      .replace(/:+$/, '')
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
