# ES6 Training – Tools and Resources

---

### What is ES6?

The latest major iteration of Javascript. 

Includes features such as object literals, string interpolation, module support, arrow functions, and more.

### Pros of using ES6
* Future of JS, start using on front-end of adoption
* All ES5 code is still valid; you can choose if/when you want to use ES6
* Greatly extends current JS functionality
* Transpilers offer source map options to aid in debugging
* Can speed up development process

### Cons of using ES6
* Adds a step to the build process (transpilation, see *Tools* below)
	* *Note*: this may not be an issue if you use Babel to compile other code, e.g. JSX/React
* While many features are new developments on the language, other features are decried as syntactic sugar. 
* Generated ES5 code may be difficult to analyze/debug (without source map) due to transpilation of high-level ES6 code to lower-level ES5

## Resources

Learn more about ES6.

* **ECMAScript Specification**: In case you want to look at the actual spec. [LINK](http://www.ecma-international.org/ecma-262/6.0/)
* **PonyFoo ES6 Series**: Published by Nicolas Bevacqua, a JS consultant, these are in-depth articles relating to individual ES6 features, their uses, and considerations. [LINK](https://ponyfoo.com/articles/tagged/es6-in-depth)
	* *ES6 Overview in 350 Bullet Points*: Quick and high-level overview of ES6 features [LINK](https://ponyfoo.com/articles/es6)
* **ESNext posts on 2ality**: 2ality is a blog from Dr. Axel Rauschmayer, a German JS app developer and author. These posts specifically look at ES6 features and concepts. [LINK](http://www.2ality.com/search/label/esnext)
	* *Exploring ES6*: Free online book that dives into ES6; for sale as a downloadable eBook starting at $28. [LINK](http://exploringjs.com/es6/index.html)

## Tools

Test out or transpile ES6.

* **Babel**: npm module that transpiles ES6 into ES5 code. Availble for use with [Grunt](https://github.com/babel/grunt-babel), [Gulp](https://github.com/babel/gulp-babel), [Browserify](https://github.com/babel/babelify), and [webpack](https://github.com/babel/babel-loader). [LINK](http://babeljs.io/)
	* *Babel REPL*: Test out ES6 on the fly, complete with ES6 output and console output. [LINK](http://babeljs.io/)
* **Caniuse: ES6**: [caniuse.com](http://caniuse.com/) compatibility tables for several ES6 features; non-exhaustive. [LINK](http://caniuse.com/#search=es6)
* **Codepen**: Codepen is an online code editor featuring many preprocessors for HTML, CSS, and JS. You can use [this template project](http://codepen.io/gd-am/pen/wKbzjY?editors=101) to try Babel and see how HTML would be affected. [LINK](http://codepen.io/)