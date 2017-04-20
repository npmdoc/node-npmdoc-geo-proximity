# npmdoc-geo-proximity

#### api documentation for  [geo-proximity (v2.3.2)](https://github.com/arjunmehta/node-geo-proximity)  [![npm package](https://img.shields.io/npm/v/npmdoc-geo-proximity.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-geo-proximity) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-geo-proximity.svg)](https://travis-ci.org/npmdoc/node-npmdoc-geo-proximity)

#### Super fast proximity searches of geo coordinates.

[![NPM](https://nodei.co/npm/geo-proximity.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/geo-proximity)

- [https://npmdoc.github.io/node-npmdoc-geo-proximity/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-geo-proximity/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-geo-proximity/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-geo-proximity/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-geo-proximity/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-geo-proximity/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arjun Mehta",
        "url": "http://www.arjunmehta.net/"
    },
    "browser": "browser.js",
    "bugs": {
        "url": "https://github.com/arjunmehta/node-geo-proximity/issues"
    },
    "dependencies": {
        "ngeohash": "~0.6.0"
    },
    "deprecated": "Deprecated in favour of GeoRedis: www.npmjs.com/georedis | github.com/arjunmehta/node-georedis",
    "description": "Super fast proximity searches of geo coordinates.",
    "devDependencies": {
        "browserify": "~9.0.3",
        "chai": "~2.1.0",
        "mocha": "~2.1.0",
        "mocha-phantomjs": "~3.5.3",
        "nodeunit": "~0.9.0",
        "redis": "~0.10.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7d0ac5a6423b450c9ffc5c08e173f09ab2c3f5b5",
        "tarball": "https://registry.npmjs.org/geo-proximity/-/geo-proximity-2.3.2.tgz"
    },
    "gitHead": "26ef0f594e0f04deabe6d1ccb5d439217c0a2f15",
    "homepage": "https://github.com/arjunmehta/node-geo-proximity",
    "keywords": [
        "geohash",
        "proximity",
        "nearby",
        "locations",
        "spatial index",
        "2D spatial index",
        "spatial",
        "index",
        "redis",
        "geolocation",
        "geoproximity",
        "radius"
    ],
    "license": "MIT",
    "main": "./main",
    "maintainers": [
        {
            "name": "arjunmehta"
        }
    ],
    "name": "geo-proximity",
    "optionalDependencies": {},
    "repository": {
        "url": "git+https://github.com/arjunmehta/node-geo-proximity.git"
    },
    "scripts": {
        "test": "nodeunit test/test.js && browserify test/browser_test.js -o test/browser_test_compiled.js && echo '\n  Testing in Browser' && mocha-phantomjs test/browser.html"
    },
    "version": "2.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
