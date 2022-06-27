
# Intro
https://redocly.com/docs/redoc/deployment/intro/


# Usage
https://redocly.com/docs/redoc/deployment/cli/#redoc-cli-examples

## Install lib
```
npm i -g @redocly/cli@latest
```

## Run locally
```
openapi preview-docs -p 8888 latestswagger2.json
```

```
openapi preview-docs -p 8888 http://petstore.swagger.io/v2/swagger.json
```

## Build html
```
redoc-cli build latestswagger2.json
```
