
<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i>yes sorry</i>
    <br>
    <br>
    <img src="https://github.com/garronej/refactored_fortnight_sorry/workflows/ci/badge.svg?branch=develop">
    <img src="https://img.shields.io/bundlephobia/minzip/refactored_fortnight_sorry">
    <img src="https://img.shields.io/npm/dw/refactored_fortnight_sorry">
    <img src="https://img.shields.io/npm/l/refactored_fortnight_sorry">
</p>

- [Home](https://github.com/garronej/refactored_fortnight_sorry)
- [Documentation](https://github.com/garronej/refactored_fortnight_sorry)



# Install / Import

``refactored_fortnight_sorry`` is both a [Deno](https://deno.land/x/refactored_fortnight_sorry) and an [NPM](https://www.npmjs.com/refactored_fortnight_sorry) module.

## Node:

```bash
$ npm install --save refactored_fortnight_sorry
```
```typescript
import { myFunction, myObject } from 'refactored_fortnight_sorry'; 
```

Specific import

```typescript
import { myFunction } from 'refactored_fortnight_sorry/myFunction';
import { myObject } from 'refactored_fortnight_sorry/myObject';
```

## Deno:

For the latest version:   
```typescript
import { myFunction, myObject } from 'https://deno.land/x/refactored_fortnight_sorry/mod.ts';
```

To import a specific [release](https://github.com/garronej/refactored_fortnight_sorry/releases):  

```typescript
import { myFunction, myObject } from 'https://deno.land/x/refactored_fortnight_sorry@0.1.0/mod.ts';
```

Specific imports:  

```typescript
import { myFunction } from 'https://deno.land/x/refactored_fortnight_sorry/myFunction.ts';
import { myObject } from 'https://deno.land/x/refactored_fortnight_sorry/myObject.ts';
```

## Import from HTML, with CDN

Import it via a bundle that creates a global ( wider browser support ):  

```html
<script src="//unpkg.com/refactored_fortnight_sorry/bundle.min.js"></script>
<script>
  const { myFunction, myObject } = refactored_fortnight_sorry;
</script>
```

Or import it as an ES module:  

```html
<script type="module">
  import { myFunction, myObject } from '//unpkg.com/refactored_fortnight_sorry/zz_esm/index.js';
</script>
```

*You can specify the version you wish to import: * [unpkg.com](https://unpkg.com)

## Contribute

```bash
npm install
npm run build
npm test
```
