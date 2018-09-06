# \<retro-web-app\>

Celebrates the beauty of 90s-style HTML with the help of Polymer custom elements (and a metric ton of JavaScript). This project depends on [retro-web-elements](https://github.com/wortwart/retro-web-elements), also published on NPM as [retro-elements](https://www.npmjs.com/package/retro-elements).

See it live: https://woerter.de/projects/retro-web/

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

Check polymer.json for build details and file path specifications. Good luck with that.
