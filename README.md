# Browserify x Modernizr

Require modernizr modules from browserify.

We are requiring Modernizr as an NPM module, pending the upcoming release of 3.0.0 which will also be available as an npm module.

Once cloned:

```
npm install
```

Build using:

```
browserify -t deamdify src/app.js -o dist/app.js
```

Launch a static webserver from root and open your browser.

Check the console.
