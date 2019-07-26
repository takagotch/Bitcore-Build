### Bitcore Build
---
https://github.com/bitpay/bitcore/tree/master/packages/bitcore-build

```js
var gulp = require('gulp');
var bitcoreTasks = require('bitcore-build');

bitcoreTasks('submodule');
gulp.task('default', ['lint', 'test', 'browser', 'coverage']);

var bitcoreTasks = require('bitcore-build');
bitcoreTasks('submodule', {skipBrowsers: true});
```

```sh
npm install bitcore-build
```

```
```


