# Spec API

Quickly spec your APIs for Swagger / OpenAPI interface. Uses @sleeksky-dev/flat-json-schema for specifying JSON schema.

# Example
```JavaScript
let refRequest = docs.ref.schema('example','{id:i:1,name:s:foo,label:{id:i:2,name:?s:bar},arr:[{a:b:false}]}');

docs.put('/:id').tag("dot-notation").req(refRequest).res(200, '{hello,world}');
```
![](https://i.ibb.co/ypWxGZJ/spec-api-ss1.png)
# Installation

npm install -s @sleeksky-dev/spec-swagger

const docs = require('@sleeksky-dev/spec-swagger');

# License

MIT © SleekSky
