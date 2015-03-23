angular-typecheck
==========

Type checking extension for Angular.js

## What is it for?

Oh look! There are [type checking methods](https://docs.angularjs.org/api/ng/function) in Angular.js! Great!

- `angular.isUndefined()`
- `angular.isDefined()`
- `angular.isObject()`
- `angular.isString()`
- `angular.isNumber()`
- `angular.isDate()`
- `angular.isArray()`
- `angular.isFunction()`

But Wait! This list is incomplete!

Let's extend this list with the missing types!

- `angular.isNull()`
- `angular.isBoolean()`
- `angular.isRegExp()`
- `angular.isNaN()`

What about the new ES6 types?

- `angular.isTypedArray()`
- `angular.isArrayBuffer()`
- `angular.isDataView()`
- `angular.isMap()`
- `angular.isSet()`
- `angular.isWeakMap()`
- `angular.isWeakSet()`
- `angular.isPromise()`
- `angular.isSymbol()`

What about a nifty JSON test?

- `angular.isJSON()`

Finally a type detection:

- `angular.detectType()`

Possible return values for *angular.detectType()*:

- `'array'`
- `'arraybuffer'`
- `'boolean'`
- `'dataview'`
- `'date'`
- `'function'`
- `'map'`
- `'null'`
- `'number'`
- `'object'`
- `'promise'`
- `'regexp'`
- `'set'`
- `'string'`
- `'symbol'`
- `'typedarray'`
- `'undefined'`
- `'weakmap'`
- `'weakset'`


## Further readings

- [MDN - JavaScript Standard built-in objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)
- [ECMAScript 5 compatibility table](https://kangax.github.io/compat-table/es5/)
- [ECMAScript 6 compatibility table](https://kangax.github.io/compat-table/es6/)


## Installation

Install manually, or from bower:

```bash
$ bower install angular-typecheck
```

## Usage

Include *angular-typecheck.min.js* in your index.html file after your AngularJS file.

```html
<script src="lib/angular-typecheck/dist/angular-typecheck.min.js"></script>
```

## Author

#### Peter Bakondy

- https://github.com/pbakondy


## LICENSE

angular-typecheck is licensed under the MIT Open Source license. For more information, see the LICENSE file in this repository.
