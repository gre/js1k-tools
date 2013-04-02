##js1k-tools

[Blog post to come..](http://www.lab4games.net/zz85/blog)

js1k-tools combies the [js1k](http://http://js1k.com/) spring 2013 [shim](http://js1k.com/2013-spring/rules), [closure compiler](https://developers.google.com/closure/compiler/), the awesome [JSCrush](http://www.iteral.com/jscrush/) with a node.js script to make life a little easier writing and packing 1k apps.

It faciliates offline js1k work, and reduces the need to copy and paste code between the browser-based minifiers and compressors.

###Instructions

1. write your code in `source.js`
2. test your code with `source.html`
3. compile your code with `node process.js`
4. test `minified.html` and `crushed.html`

While working on my [js1k entry](http://js1k.com/2013-spring/demo/1542), I found it useful to have this environment/boilerplate/toolkit. (Sidenote: Any serious javascript developers should try writing an application in 1024 bytes at least once!)

Each javascript file accompanying html files comes with each respective, so its easy to check what stops working along the way.

`source.html` / `source.js` -> your raw unminified source code

`minified.html` / `minified.js` -> minified source generated by the closure compiler

`crushed.html` / `crushed.js` -> the final compressed code

`externs.js` - for declaring variables to be untouch by closure.

###TODO
Add Siorki's [RegPack](https://github.com/Siorki/RegPack) to save more bytes!

questions or comments? ask [@blurspline](http://twitter.com/blurspline)