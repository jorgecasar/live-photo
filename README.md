[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/jorgecasar/live-photo)

# \<live-photo\>

Live Photo from Apple implemented in Polymer

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="live-photo.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<live-photo id="livePhoto" photo-src="demo/assets/boy.jpg" video-src="demo/assets/boy.mov" preload></live-photo>
<live-photo id="livePhoto" photo-src="demo/assets/girl.jpg" video-src="demo/assets/girl.mov" no-controls></live-photo>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
