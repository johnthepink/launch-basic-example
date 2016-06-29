# Launch Basic Example

[![Build Status](https://travis-ci.org/NewSpring/launch-basic-example.svg?branch=master)](https://travis-ci.org/NewSpring/launch-basic-example)

## Secrets

```
tar cvf secrets.tar launch.json .keystore deployment_token.json
travis encrypt-file secrets.tar .travis/secrets.tar.enc
```
