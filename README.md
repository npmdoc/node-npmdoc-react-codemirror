# npmdoc-react-codemirror

#### api documentation for  [react-codemirror (v0.3.0)](https://github.com/JedWatson/react-codemirror)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-codemirror.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-codemirror) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-codemirror.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-codemirror)

#### Codemirror

[![NPM](https://nodei.co/npm/react-codemirror.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-codemirror)

- [https://npmdoc.github.io/node-npmdoc-react-codemirror/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-codemirror/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-codemirror/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-codemirror/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-codemirror/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-codemirror/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jed Watson"
    },
    "browserify-shim": {
        "react": "global:React"
    },
    "bugs": {
        "url": "https://github.com/JedWatson/react-codemirror/issues"
    },
    "dependencies": {
        "classnames": "^2.2.5",
        "codemirror": "^5.18.2",
        "lodash.debounce": "^4.0.8"
    },
    "description": "Codemirror",
    "devDependencies": {
        "gulp": "^3.9.1",
        "happiness": "^7.1.2",
        "react": "^15.3.1",
        "react-component-gulp-tasks": "^0.7.7",
        "react-dom": "^15.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "cd6bd6ef458ec1e035cfd8b3fe7b30c8c7883c6c",
        "tarball": "https://registry.npmjs.org/react-codemirror/-/react-codemirror-0.3.0.tgz"
    },
    "gitHead": "930600810e5ceb4ad426a66098ecf1404d9e32c3",
    "happiness": {
        "ignore": [
            "**/.publish/**",
            "**/dist/**",
            "**/lib/**"
        ]
    },
    "homepage": "https://github.com/JedWatson/react-codemirror",
    "keywords": [
        "react",
        "react-component",
        "codemirror",
        "editor",
        "code"
    ],
    "license": "MIT",
    "main": "lib/Codemirror.js",
    "maintainers": [
        {
            "name": "jedwatson"
        }
    ],
    "name": "react-codemirror",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.14 <16",
        "react-dom": ">=0.14 <16"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/JedWatson/react-codemirror.git"
    },
    "scripts": {
        "build": "gulp clean && NODE_ENV=production gulp build",
        "bump": "gulp bump",
        "bump:major": "gulp bump:major",
        "bump:minor": "gulp bump:minor",
        "examples": "gulp dev:server",
        "lint": "happiness",
        "publish:site": "gulp publish:examples",
        "release": "gulp release",
        "start": "gulp dev",
        "test": "echo \"no tests yet\" && exit 0",
        "watch": "gulp watch:lib"
    },
    "version": "0.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
