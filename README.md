# SwaggerTemplateRepo API Specification
[![Build Status](https://travis-ci.org/Rebilly/SwaggerTemplateRepo.svg?branch=master)](https://travis-ci.org/Rebilly/SwaggerTemplateRepo)

## Installing

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
    + Run `npm install`

## Usage

- Run `npm start`
- Look full spec:
    + JSON [http://localhost:3000/swagger.json](http://localhost:3000/swagger.json)
    + YAML [http://localhost:3000/swagger.yaml](http://localhost:3000/swagger.yaml)  (may not be fully functional)
- Browse Swagger UI:
    + JSON [http://localhost:3000/swagger-ui/?url=http://localhost:3000/swagger.json](http://localhost:3000/?url=http://localhost:3000/swagger.json)
    + YAML [http://localhost:3000/swagger-ui/?url=http://localhost:3000/swagger.yaml](http://localhost:3000/?url=http://localhost:3000/swagger.yaml)  (may not be fully functional)
- Browse ReDoc: [http://localhost:3000/](http://localhost:3000/)
- Preview spec version for branch `<branch>` (**doesn't work locally**): [http://Rebilly.github.io/SwaggerTemplateRepo/preview/&lt;branch&gt;](http://Rebilly.github.io/SwaggerTemplateRepo/preview/<branch>)
**!** Branch preview is not available until Travis CI deploy it
- Import spec by URL in editor, online or local (you should uncheck "Use CORS proxy" in the model)

## Tests

Run command from project root directory:

```bash
npm test
```
