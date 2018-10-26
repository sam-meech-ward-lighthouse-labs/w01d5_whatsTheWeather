# Modules and Testing

## Modules 

What is a module and what problem does it solve?

* Allows us to separate the problem into bite size pieces. 
* Encapsulation, reuse.
* Files in Node are Modules.
* Makes debugging process easier.
  - We can separate our test code from our production code. 
* Easier to read. 
* keeps global scope clean.

Every module in node gets wrapped inside this function:

```js
(function (exports, require, module, __filename, __dirname) {
})()
```

exports is an empty object.
require is a function
module is an object

When we require a module `require('./somemodeul')`, we get that module's `exports` object. `require` returns a module's exports object.

Everything in a node module is private to that file. The only thing that we can access from another file is that file's `exports` object. If we want to be able to access anything from a module, we can attach it to the `exports` object.

## npm

- package.json 
- `npm init`
- `-g`

## mocha



---



## Snippets

```js
```
