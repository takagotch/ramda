### ramda
---
https://github.com/ramda/ramda

https://github.com/CrossEye/ramda

```
npm install ramda
npm run --silent partial-build compose reduce filter > dist/ramda.custom.js
npm install -g mocha
mocha
npm install
npm test
```

```js
const R = require('ramda');

import * as R from 'ramda'
const {} = R
R.map(identity, [1, 2, 3])

import identity from 'ramda/src/identity'
identity()
```

```
<script src="path/to/yourCopyOf/ramda.js"></script>
<script src="path/to/yourCopyOf/ramda.min.js"></script>
```

```js
const greet = R.replace('{name}', R._, 'Hello, {name}!');
greet('Alice');

R.add(2, 3);
R.add(7)(10);

const mapIndexed = R.addIndex(R.map);
mapIndexed((val, idx) => idx + '-' + val, ['f', 'o', 'o', 'b', 'a', 'r']);
```

