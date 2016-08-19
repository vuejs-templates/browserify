# vue-browserify-boilerplate

> A full-featured Browserify + `vueify` setup with hot-reload, linting & unit testing.

> This template is Vue 2.0 compatible. For Vue 1.x use this command: `vue init browserify#1.0 my-project`

### Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli).

``` bash
$ npm install -g vue-cli
$ vue init browserify my-project
$ cd my-project
$ npm install
$ npm run dev
```

### What's Included

- `npm run dev`: Browserify + `vueify` with proper config for source map & hot-reload.

- `npm run build`: Production build with HTML/CSS/JS minification.

- `npm run lint`: Lint JavaScript and `*.vue` files with ESLint.

- `npm test`: Unit tests in PhantomJS with Karma + karma-jasmine + karma-browserify, with support for mocking and ES2015.

For more information see the [docs for vueify](https://github.com/vuejs/vueify).

### Customizations

You will likely need to do some tuning to suit your own needs:

- Install additional libraries that you need, e.g. `vue-router`, `vue-resource`, `vuex`, etc...

- Use your preferred `.eslintrc` config. Don't forget to keep the plugin field so that ESLint can lint `*.vue` files.

- Add your preferred CSS pre-processor, for example:

  ``` bash
  npm install less --save-dev
  ```

  Then you can do:

  ``` vue
  <style lang="less">
    /* write less! */
  </style>
  ```

- The dev build is served using [http-server](https://github.com/indexzero/http-server). You can edit the NPM dev script in `package.json` to add a proxy option so that ajax requests are proxied to a separate backend API.

- For unit testing:

  - You can run the tests in multiple real browsers by installing more [karma launchers](http://karma-runner.github.io/0.13/config/browsers.html) and adjusting the `browsers` field in `karma.conf.js`.

  - You can also swap out Jasmine for other testing frameworks, e.g. use Mocha with [karma-mocha](https://github.com/karma-runner/karma-mocha).

### Fork It And Make Your Own

You can fork this repo to create your own boilerplate, and use it with `vue-cli`:

``` bash
vue init username/repo my-project
```
