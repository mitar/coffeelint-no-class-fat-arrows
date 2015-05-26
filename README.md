coffeelint-no-class-fat-arrows
==============================

CoffeeLint rule which forbids fat arrows for object methods.

Description
-----------

This [CoffeeLint](http://www.coffeelint.org/) rule verifies that object methods are not defined
with a fat arrow. This is useful for the code style where caller is expected to assure calls
of object methods are bound with the correct `this` value.

Installation
------------

```sh
npm install coffeelint-no-class-fat-arrows
```

Usage
-----

Add the following configuration to `coffeelint.json`:

```json
"no_class_fat_arrows": {
  "module": "coffeelint-no-class-fat-arrows"
}
```

Configuration
-------------

There are currently no configuration options.
