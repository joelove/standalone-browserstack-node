# Standalone cross-browser testing suite
## Utilises Node, WebdriverIO, Selenium and BrowserStack

### Installation

```
npm install
```

### Building the test suite

The tests are written in ES6/7 so need to be built with Babel before they can be run.

```
npm run build
```

### Linting the app

You can lint the app with ESlint manually by running:

```
npm run lint
```

### Notes

You may want to use (Direnv)[https://github.com/direnv/direnv] to keep track of environment variable for you. An example .envrc can be found at `.envrc.example`.
