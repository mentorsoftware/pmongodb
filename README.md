# promised-mongo

Promises wrapper for mongodb driver.


## Install
pmongodb is available through [npm](http://npmjs.org):

	npm install pmongodb

## Documentation

The documentation below refers to an older version.  Most of it should still work the same however.
Watch this space for improvements.


## Usage

Use promised-mongo just like mongojs, except that you use the returned promise instead of a
callback.

```js
var pmongo = require('promised-mongo');
var db = pmongo(connectionString, [collections]);
```