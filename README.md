<!--

@license Apache-2.0

Copyright (c) 2022 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# uppercase

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Convert a string to uppercase.

<section class="intro">

</section>

<!-- /.intro -->



<section class="usage">

## Usage

To use in Observable,

```javascript
uppercase = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/string-base-uppercase@umd/browser.js' )
```
The previous example will load the latest bundled code from the umd branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/string-base-uppercase/tags). For example,

```javascript
uppercase = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/string-base-uppercase@v0.0.2-umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var uppercase = require( 'path/to/vendor/umd/string-base-uppercase/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/string-base-uppercase@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.uppercase;
})();
</script>
```

#### uppercase( str )

Converts a string to uppercase.

```javascript
var str = uppercase( 'bEEp' );
// returns 'BEEP'
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/string-base-uppercase@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var str = uppercase( 'Beep' );
// returns 'BEEP'

str = uppercase( 'BeEp' );
// returns 'BEEP'

str = uppercase( 'Beep BOOP' );
// returns 'BEEP BOOP'

str = uppercase( '$**_beep_BoOp_**$' );
// returns '$**_BEEP_BOOP_**$'

str = uppercase( '' );
// returns ''

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/string-base-uppercase.svg
[npm-url]: https://npmjs.org/package/@stdlib/string-base-uppercase

[test-image]: https://github.com/stdlib-js/string-base-uppercase/actions/workflows/test.yml/badge.svg?branch=v0.0.2
[test-url]: https://github.com/stdlib-js/string-base-uppercase/actions/workflows/test.yml?query=branch:v0.0.2

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/string-base-uppercase/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/string-base-uppercase?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/string-base-uppercase.svg
[dependencies-url]: https://david-dm.org/stdlib-js/string-base-uppercase/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/string-base-uppercase/tree/deno
[umd-url]: https://github.com/stdlib-js/string-base-uppercase/tree/umd
[esm-url]: https://github.com/stdlib-js/string-base-uppercase/tree/esm
[branches-url]: https://github.com/stdlib-js/string-base-uppercase/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/string-base-uppercase/main/LICENSE

</section>

<!-- /.links -->
