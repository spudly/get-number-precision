# @spudly/get-number-precision

Returns the number of digits after the decimal point for a number.

# Installation

```bash
npm install --save @spudly/get-number-precision
```

# Usage

```js
import getNumberPrecision from '@spudly/get-number-precision';

getNumberPrecision(1); // => 0
getNumberPrecision(1.01); // => 2
getNumberPrecision(1.2); // => 1
getNumberPrecision(1.2); // => 1
getNumberPrecision(1.23); // => 2
getNumberPrecision(1.234); // => 3
getNumberPrecision(1.2345); // => 4
getNumberPrecision(1.23456); // => 5
getNumberPrecision(NaN); // => 0
getNumberPrecision(Infinity); // => 0
getNumberPrecision(-Infinity); // => 0
```
