# reproduce-playwright-22579

reproduce-playwright-22579

## Reproduce

```sh
$ npm install
$ npm init -y playwright template
... JavaScript
... all defaults
$ mkdir tests
$ cp template/playwright.config.js playwright.config.cjs
$ cp template/tests/example.spec.js tests/example.spec.cjs
$ npm exec -- playwright test --project=firefox
Error: No named projects are specified in the configuration file




```
