# npmdoc-airsonos

#### api documentation for  airsonos (v0.2.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-airsonos.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-airsonos) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-airsonos.svg)](https://travis-ci.org/npmdoc/node-npmdoc-airsonos)

#### AirTunes to Sonos devices

[![NPM](https://nodei.co/npm/airsonos.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/airsonos)

- [https://npmdoc.github.io/node-npmdoc-airsonos/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-airsonos/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-airsonos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-airsonos/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-airsonos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-airsonos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "airsonos",
    "version": "0.2.6",
    "author": "Stephen Wan <stephen@stephenwan.net>",
    "description": "AirTunes to Sonos devices",
    "contributors": [
        {
            "name": "Stephen Wan"
        }
    ],
    "scripts": {
        "start": "babel-node ./lib/index.js",
        "test": "jscs .",
        "prepublish": "babel ./lib/ -d ./bin/"
    },
    "bin": "./bin/index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/stephen/airsonos.git"
    },
    "dependencies": {
        "babel": "^5.8.21",
        "bluebird": "^2.9.34",
        "flags": "~0.1.2",
        "ip": "1.1.0",
        "nicercast": "0.1.0",
        "nodetunes": "^0.3.0",
        "sonos": "git://github.com/stephen/node-sonos.git#stephen-1.0.0"
    },
    "license": "MIT",
    "devDependencies": {
        "jscs": "^2.1.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
