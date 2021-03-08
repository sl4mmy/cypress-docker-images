# cypress/browsers:node14.16.0-chrome89-ff78

A complete image with all operating system dependencies for Cypress, Chrome
89 and Firefox 78 browsers.

[Dockerfile](Dockerfile)

```text
node version:    v14.16.0
npm version:     6.14.11
yarn version:    1.22.10
debian version:  10.8
Chrome version:  Google Chrome 89.0.4389.82
Firefox version: Mozilla Firefox 78.8.0esr
git version:     git version 2.20.1
whoami:          root
```

**Note:** this image uses the `root` user. You might want to switch to non-root
user like `node` when running this container for security.