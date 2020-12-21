# Installation

```bash
$ npm install nib@https://github.com/wtlizzz/nib.git
```

 If the image generation features of Nib are desired, such as generating the linear gradient images, install [node-canvas](http://github.com/learnboost/node-canvas):

```bash
$ npm install canvas
```

# Fix Warn 
```
(node:3099) Warning: Accessing non-existent property 'lineno' of module exports inside circular dependency
(Use `node --trace-warnings ...` to show where the warning was created)
(node:3099) Warning: Accessing non-existent property 'column' of module exports inside circular dependency
(node:3099) Warning: Accessing non-existent property 'filename' of module exports inside circular dependency
(node:3099) Warning: Accessing non-existent property 'lineno' of module exports inside circular dependency
(node:3099) Warning: Accessing non-existent property 'column' of module exports inside circular dependency
(node:3099) Warning: Accessing non-existent property 'filename' of module exports inside circular dependency

```

```
(node:2754) Warning: Accessing non-existent property 'lineno' of module exports inside circular dependency
    at emitCircularRequireWarning (internal/modules/cjs/loader.js:853:11)
    at Object.get (internal/modules/cjs/loader.js:867:5)
    at Boolean.Node [as constructor] (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/node.js:42:23)
    at new Boolean (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/boolean.js:23:8)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/index.js:57:16)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
    at Module.require (internal/modules/cjs/loader.js:1145:19)
    at require (internal/modules/cjs/helpers.js:75:18)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/lexer.js:13:13)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
(node:2754) Warning: Accessing non-existent property 'column' of module exports inside circular dependency
    at emitCircularRequireWarning (internal/modules/cjs/loader.js:853:11)
    at Object.get (internal/modules/cjs/loader.js:867:5)
    at Boolean.Node [as constructor] (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/node.js:43:23)
    at new Boolean (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/boolean.js:23:8)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/index.js:57:16)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
    at Module.require (internal/modules/cjs/loader.js:1145:19)
    at require (internal/modules/cjs/helpers.js:75:18)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/lexer.js:13:13)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
(node:2754) Warning: Accessing non-existent property 'filename' of module exports inside circular dependency
    at emitCircularRequireWarning (internal/modules/cjs/loader.js:853:11)
    at Object.get (internal/modules/cjs/loader.js:867:5)
    at Boolean.Node [as constructor] (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/node.js:44:25)
    at new Boolean (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/boolean.js:23:8)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/index.js:57:16)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
    at Module.require (internal/modules/cjs/loader.js:1145:19)
    at require (internal/modules/cjs/helpers.js:75:18)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/lexer.js:13:13)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
(node:2754) Warning: Accessing non-existent property 'lineno' of module exports inside circular dependency
    at emitCircularRequireWarning (internal/modules/cjs/loader.js:853:11)
    at Object.get (internal/modules/cjs/loader.js:867:5)
    at Boolean.Node [as constructor] (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/node.js:42:23)
    at new Boolean (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/boolean.js:23:8)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/index.js:58:17)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
    at Module.require (internal/modules/cjs/loader.js:1145:19)
    at require (internal/modules/cjs/helpers.js:75:18)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/lexer.js:13:13)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
(node:2754) Warning: Accessing non-existent property 'column' of module exports inside circular dependency
    at emitCircularRequireWarning (internal/modules/cjs/loader.js:853:11)
    at Object.get (internal/modules/cjs/loader.js:867:5)
    at Boolean.Node [as constructor] (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/node.js:43:23)
    at new Boolean (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/boolean.js:23:8)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/index.js:58:17)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
    at Module.require (internal/modules/cjs/loader.js:1145:19)
    at require (internal/modules/cjs/helpers.js:75:18)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/lexer.js:13:13)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
(node:2754) Warning: Accessing non-existent property 'filename' of module exports inside circular dependency
    at emitCircularRequireWarning (internal/modules/cjs/loader.js:853:11)
    at Object.get (internal/modules/cjs/loader.js:867:5)
    at Boolean.Node [as constructor] (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/node.js:44:25)
    at new Boolean (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/boolean.js:23:8)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/nodes/index.js:58:17)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)
    at Module.require (internal/modules/cjs/loader.js:1145:19)
    at require (internal/modules/cjs/helpers.js:75:18)
    at Object.<anonymous> (/Users/lli/Documents/hexo-workspace/hexo-blog/node_modules/nib/node_modules/stylus/lib/lexer.js:13:13)
    at Module._compile (internal/modules/cjs/loader.js:1256:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1277:10)
    at Module.load (internal/modules/cjs/loader.js:1105:32)
    at Function.Module._load (internal/modules/cjs/loader.js:967:14)

```


[![Build Status](https://travis-ci.org/stylus/nib.svg?branch=master)](https://travis-ci.org/stylus/nib)

# Nib

  Stylus mixins, utilities, components, and gradient image generation. Don't forget to check out the [documentation](http://stylus.github.io/nib/).



## JavaScript API

 Below is an example of how to utilize nib and stylus with the connect framework (or express).

```javascript
var connect = require('connect')
  , stylus = require('stylus')
  , nib = require('nib');

var server = connect();

function compile(str, path) {
  return stylus(str)
	.set('filename', path)
	.set('compress', true)
	.use(nib());
}

server.use(stylus.middleware({
	src: __dirname
  , compile: compile
}));
```

## Stylus API

  To gain access to everything nib has to offer, simply add:

  ```css
  @import 'nib'
  ```

  Or you may also pick and choose based on the directory structure in `./lib`, for example:

  ```css
  @import 'nib/gradients'
  @import 'nib/overflow'
  @import 'nib/normalize'
  ```

_To be continued..._

## More Information

  - Introduction [screencast](http://www.screenr.com/M6a)

## Testing

 You will first need to install the dependencies:

 ```bash
    $ npm install -d
 ```

 Run the automated test cases:

 ```bash
    $ npm test
 ```

 For visual testing run the test server:

 ```bash
    $ npm run-script test-server
 ```

 Then visit `localhost:3000` in your browser.

## Contributors

I would love more contributors. And if you have helped out, you are awesome! I want to give a huge thanks to these people:

  - [TJ Holowaychuk](https://github.com/tj) (Original Creator)
  - [Sean Lang](https://github.com/slang800) (Current Maintainer)
  - [Isaac Johnston](https://github.com/superstructor)
  - [Everyone Else](https://github.com/tj/nib/contributors)
