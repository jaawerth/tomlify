@jaawerth/tomlify
=======

**Note:** *Forked from [BinaryMuse/tomlify](https://github.com/BinaryMuse/tomlify) for temporary scoped publishing until original is published*

[TOML](https://github.com/BinaryMuse/toml-node) all up in your [Browserify](http://browserify.org/).

Installation
------------

```
npm install [--save] browserify @jaawerth/tomlify
```

Usage
-----

```javascript
// inside client.js
var myConfig = require('./config.toml');
```

```
browserify -t @jaawerth/tomlify client.js
```

License
-------

tomlify is licensed under the MIT license. See the LICENSE file for more information.
