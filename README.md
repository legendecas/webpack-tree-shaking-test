# webpack tree-shaking test

This example shows how webpack production mode strips unused `@opentelemetry/semantic-conventions` attributes.

```sh
$ npm run build
```

The output in `dist/main.js` should only contains used attributes of `@opentelemetry/semantic-conventions`.

Related issues:
- [Tree shake re-exported namespaces](https://github.com/webpack/webpack/issues/9607)
- [Tree shake object literals](https://github.com/webpack/webpack/issues/9688)
