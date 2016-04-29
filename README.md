# react-barcode
<img src="https://raw.githubusercontent.com/kciter/react-barcode/master/images/barcode.png" alt="barcode">
Preview: http://kciter.github.io/react-barcode/

A `<Barcode/>` component for use with React.<br>
This library is wrapped by [JsBarcode](https://github.com/lindell/JsBarcode)

## Installation
```
npm install react-barcode
```

## Usage
```js
var React = require('react');
var Barcode = require('react-barcode');

React.render(
  <Barcode value="http://github.com/kciter" />,
  mountNode
);
```

## Options:

For information about how to use the options, see [the wiki page](https://github.com/lindell/JsBarcode/wiki/Options).
```
{
  width: 2,
  height: 100,
  format: "CODE128",
  displayValue: true,
  fontOptions: "",
  font: "monospace",
  textAlign: "center",
  textPosition: "bottom",
  textMargin: 2,
  fontSize: 20,
  background: "#ffffff",
  lineColor: "#000000",
  margin: 10,
  marginTop: undefined,
  marginBottom: undefined,
  marginLeft: undefined,
  marginRight: undefined
}
```

## Reference
* https://github.com/lindell/JsBarcode
* https://github.com/zpao/qrcode.react

## Licence
Copyright (c) 2016, Lee Sun-Hyoup

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
