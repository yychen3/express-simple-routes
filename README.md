<h1 align="center">Welcome to express-simple-routes 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/express-simple-routes" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/express-simple-routes.svg">
  </a>
  <a href="https://github.com/olliecee/express-simple-routes#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/olliecee/express-simple-routes/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
</p>

> Simple Routes can use single or multiple directories of routes with optional authentication middleware and filters. 

### 🏠 [Homepage](https://github.com/olliecee/express-simple-routes#readme)

## Requirements
> express 4.x or higher

## Install

```sh
npm install express-simple-routes --save
```

## Usage

```javascript
const express = require("express")
const routes = require('express-simple-routes')
const app = express()

routes(app, [options])
    .authenticate([authMiddleware]),
    .validate()
    .listen(4000, () => {
        console.log('🚀 Server ready')
    })
```

Simple Routes: `[options]`

| Property | Description | Type | Default |
| --- | --- | --- | --- |
| routes | This is used to determine the directories | Array | `["src/routes"]` |
| ignore | Controls which files get ignored | Array | `[]`

## Author

👤 **olliecee <hello@olliecee.com> (https://olliecee.com)**

* Website: [olliecee.com](https://olliecee.com)
* Github: [@olliecee](https://github.com/olliecee)
* LinkedIn: [@linkedin.com\/in\/olliecee](https://linkedin.com/in/linkedin.com\/in\/olliecee)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/olliecee/express-simple-routes/issues). You can also take a look at the [contributing guide](https://github.com/olliecee/express-simple-routes/blob/master/CONTRIBUTING.md).

## Show your support

Give a ⭐️ if this project helped you!
