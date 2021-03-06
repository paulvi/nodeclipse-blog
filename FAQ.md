
## General

### How to start using Nodeclipse with existing Node.js project?

Just select existing location with new Node Project Wizard  
File -> New -> Node Project

This will add Eclipse .project file, and shows your files in Project Explorer.

### I got out of memory error!

Enable Preferences -> General -> Show heap status

Check your memory usage before and after Nodeclipse usage.
Likely you are already running low on memory, configure your Eclipse.

NOTE Eclipse runtime doesn't load plugin, until it is used (aka lazy loading).  

## chromedevtools

### What will happen if user already had standard chromedevtools and installs Nodeclipse 0.2 ?
 
The current version of standard chromedevtools is 0.3.8.
The version of chromedevtools, which Nodeclipse 0.2 bundles, is 0.3.9.
 
So, chromedevtools  will be over-written to  0.3.9.
 
### What will happen if user installs standard chromedevtools after Nodeclipse 0.2 ?

Chromedevtools will not be over-written to 0.3.8. It will  remain 0.3.9.
 
But we must always keep in mind the current version of standard chromedevtools.


### So what will happen if chromedevtools 0.3.9 or chromedevtools 0.4.0 are released?

We must update the version of our chromedevtools to 0.4.1 ASAP.
Otherwise, Nodeclipse will not work correctly. But it will be affected only for debugging features.

## Markdown Editor

### Where to get support for Markdown Editor?

Read information on [site](http://www.winterwell.com/software/markdown-editor.php)
File an issue on [gitHub](https://github.com/winterstein/Eclipse-Markdown-Editor-Plugin/issues) 

## JSHint

### What is JSHint?

[JSHint](http://www.jshint.com/) (from [Wikipedia](http://en.wikipedia.org/wiki/JSHint) )
 is a static code analysis tool for JavaScript.
[JSHint](http://www.jshint.com/) is a tool to detect errors and potential problems in JavaScript. 
