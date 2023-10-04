<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# FLOAT32_SMALLEST_SUBNORMAL

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Smallest positive **denormalized** [single-precision floating-point number][ieee754].



<section class="usage">

## Usage

<!-- eslint-disable id-length -->

```javascript
import FLOAT32_SMALLEST_SUBNORMAL from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float32-smallest-subnormal@esm/index.mjs';
```
The previous example will load the latest bundled code from the esm branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/constants-float32-smallest-subnormal/tags). For example,

```javascript
import FLOAT32_SMALLEST_SUBNORMAL from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float32-smallest-subnormal@v0.1.1-esm/index.mjs';
```

#### FLOAT32_SMALLEST_SUBNORMAL

Smallest positive **denormalized** [single-precision floating-point number][ieee754].

<!-- eslint-disable id-length -->

```javascript
var bool = ( FLOAT32_SMALLEST_SUBNORMAL === 1.401298464324817e-45 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better example -->

<!-- eslint no-undef: "error" -->

<!-- eslint-disable id-length -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import FLOAT32_SMALLEST_SUBNORMAL from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float32-smallest-subnormal@esm/index.mjs';

console.log( FLOAT32_SMALLEST_SUBNORMAL );
// => 1.401298464324817e-45

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- C interface documentation. -->



<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/constants-float32/smallest-normal`][@stdlib/constants/float32/smallest-normal]</span><span class="delimiter">: </span><span class="description">smallest positive normalized single-precision floating-point number.</span>
-   <span class="package-name">[`@stdlib/constants-float64/smallest-subnormal`][@stdlib/constants/float64/smallest-subnormal]</span><span class="delimiter">: </span><span class="description">smallest positive double-precision floating-point number.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-float32-smallest-subnormal.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-float32-smallest-subnormal

[test-image]: https://github.com/stdlib-js/constants-float32-smallest-subnormal/actions/workflows/test.yml/badge.svg?branch=v0.1.1
[test-url]: https://github.com/stdlib-js/constants-float32-smallest-subnormal/actions/workflows/test.yml?query=branch:v0.1.1

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-float32-smallest-subnormal/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-float32-smallest-subnormal?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-float32-smallest-subnormal.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-float32-smallest-subnormal/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-float32-smallest-subnormal/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-float32-smallest-subnormal/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-float32-smallest-subnormal/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-float32-smallest-subnormal/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-float32-smallest-subnormal/main/LICENSE

[ieee754]: https://en.wikipedia.org/wiki/IEEE_754-1985

<!-- <related-links> -->

[@stdlib/constants/float32/smallest-normal]: https://github.com/stdlib-js/constants-float32-smallest-normal/tree/esm

[@stdlib/constants/float64/smallest-subnormal]: https://github.com/stdlib-js/constants-float64-smallest-subnormal/tree/esm

<!-- </related-links> -->

</section>

<!-- /.links -->
