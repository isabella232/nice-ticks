# nice-ticks
Nice Ticks for Node.JS and Browser

## Install
```sh
npm install nice-ticks
```
## For Browser
```html
<script src="path-to/nice-ticks/dist/nice-ticks.js"></script>
```

## Usage
```js
const niceTicks = require("nice-ticks");

var minValue = 0.81;
var maxValue = 12.3
var numTicks = 4; //default

var ticks = niceTicks(minValue, maxValue, numTicks);

console.log(ticks);
//[0, 5, 10, 15]

```

[more test cases](./test/test.js)


## Reference
"Nice Numbers for Graph Labels", Graphics Gems, pp 61-63.  