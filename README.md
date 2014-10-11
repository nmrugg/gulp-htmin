# gulp-htmin

Minify HTML via <a href="https://github.com/gulpjs/gulp/">`gulp`</a>.

## Getting Started
Install the module with: `npm install gulp-htmin --save-dev`

## Usage

```js
var gulp = require("gulp");
var htmin = require("gulp-htmin");

gulp.task("minify", function() {
  gulp.src("src/*.html")
    .pipe(htmin({collapseWhitespace: true}))
    .pipe(gulp.dest("dist"))
});
```

See the <a href="https://github.com/kangax/html-minifier">html-minifer docs</a> for options.

## Fork

This began as a fork of <a href="https://github.com/jonschlinkert/gulp-htmlmin">gulp-htmlmin</a>.

## License
<a href="http://nate.mit-license.org/">MIT</a>
