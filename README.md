Angular-JSDoc
=============
JSDoc 3 Template for AngularJS.  
A JSDoc plugin and template for AngularJS, nothing else!  

Blog: [Sigh, AngularJS Documentation](http://allenhwkim.tumblr.com/post/92161523693/sigh-angularjs-documentation)

<img src=http://i.imgur.com/FPo9x25.gif width=50%  />

Features
----------
  * Right side TOC, table of contents,  for navigation by Directives, Services, Controllers, etc
  * Read and process @ngdoc tag

How Does It Look Like?
------------------------
  * [angularjs-google-maps Documentation](https://rawgit.com/allenhwkim/angularjs-google-maps/master/build/docs/index.html)


Install
-------

    $ npm install jsdoc angular-jsdoc --save-dev

Usage
--------

    var angularJsdoc = require('angualr-jsdoc');

    angularJsdoc(['../angularjs-google-maps/directives', '../angularjs-google-maps/services'], {
      configure: ...
      destination: ...
      template: 'tomorrow-night', 
      readme: "../angularjs-google-maps/README.md"
    });

Example
--------

   - Directive: sample-codes/ngmap/map.js [Output]()
   - Service: sample-codes/ngmap/attr2-optins.js [Output]()
   - Controller: sample-codes/ngmap/mpa-controller.js [Output]()


default/
├── css
│   ├── jsdoc-default.css 
│   └── prettify.css
├── html
│   ├── class.html
│   └── layout.html
├── js
│   └── prettify.js
└── publish.js
