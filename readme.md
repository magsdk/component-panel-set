Panel set component
===================

[![build status](https://img.shields.io/travis/magsdk/component-panel-set.svg?style=flat-square)](https://travis-ci.org/magsdk/component-panel-set)
[![npm version](https://img.shields.io/npm/v/mag-component-panel-set.svg?style=flat-square)](https://www.npmjs.com/package/mag-component-panel-set)
[![dependencies status](https://img.shields.io/david/magsdk/component-panel-set.svg?style=flat-square)](https://david-dm.org/magsdk/component-panel-set)
[![devDependencies status](https://img.shields.io/david/dev/magsdk/component-panel-set.svg?style=flat-square)](https://david-dm.org/magsdk/component-panel-set?type=dev)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-blue.svg?style=flat-square)](https://gitter.im/DarkPark/magsdk)


Panel set is a component to build user interface, an instance of [Component](https://github.com/stbsdk/component) module. Use with [mag-component-panel](https://github.com/magsdk/component-panel).


## Installation ##

```bash
npm install mag-component-panel-set
```


## Usage ##

Add the singleton to the scope:

```js
var PanelSet = require('mag-component-panel-set');
```

Create instance with custom config:

```js
var panelSet = new PanelSet({
        visible: false,
        // list of mag-component-panel panels
        panels: [leftPanel, rightPanel]
    });
```

## Development mode ##

> There is a global var `DEVELOP` which activates additional consistency checks and protection logic not available in release mode.


## Contribution ##

If you have any problem or suggestion please open an issue [here](https://github.com/magsdk/component-panel-set/issues).
Pull requests are welcomed with respect to the [JavaScript Code Style](https://github.com/DarkPark/jscs).


## License ##

`mag-component-panel-set` is released under the [MIT License](license.md).
