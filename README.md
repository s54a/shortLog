# shortLog

Do console.log() with just log()

## Installation

```js
npm i shortlog
```

### How to Use

```js
const log = require("shortlog");

log("Hello from shortlog");
```

Below is the code in the shortlog index.js file

```js
function log(val) {
  return console.log(val);
}

module.exports = log;
```
