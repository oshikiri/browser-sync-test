# browser-sync-test

```
$ git clone https://github.com/shinespark/browser-sync-test
$ npm install
$ patch -u node_modules/browser-sync/dist/server/utils.js < turn-off-getSnippetMiddleware.patch
$ ./node_modules/.bin/browser-sync start --config bs-config.js
see http://localhost:3000/test.html. and scroll down.
You see some character corruptions.
```
