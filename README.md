# [AngularStrap v2](http://mgcrea.github.io/angular-strap) [![Build Status](https://secure.travis-ci.org/mgcrea/angular-strap.png?branch=master)](http://travis-ci.org/#!/mgcrea/angular-strap)

AngularStrap is a set of native directives that enables seamless integration of [Twitter Bootstrap 3.0+](https://twitter.github.com/bootstrap) into your [AngularJS 1.2.0+](https://github.com/angular/angular.js) app.

The project is currently being rewritten from the ground up to leverage AngularJS animations that came with the v1.2 release along the new Twitter Bootstrap v3.0 markup.



## Documentation and examples

+ Check the [documentation](http://mgcrea.github.io/angular-strap) and [changelog](https://github.com/mgcrea/angular-strap/wiki/Changelog).

+ Use & fork the available [plunkers](https://github.com/mgcrea/angular-strap/wiki/Plunkers) to test a directive or report an issue.



## Quick start

+ Include the required libraries (cdn/local)

>
``` html
<script src="//ajax.googleapis.com/ajax/libs/angularjs/1.2.6/angular.min.js"></script>
<script src="//rawgithub.com/mgcrea/angular-strap/master/dist/angular-strap.js"></script>
```

+ Inject the `ngStrap` module into your app

>
``` javascript
angular.module('myApp', ['ngStrap']);
```


## Developers

Clone the repo, `git clone git://github.com/mgcrea/angular-strap.git`, [download the latest release](https://github.com/mgcrea/angular-strap/zipball/master) or install with bower `bower install angular-strap`.

AngularStrap is tested with `karma` against the latest stable release of AngularJS.

>
	$ npm install grunt-cli --global
	$ npm install --dev
	$ grunt test

You can build the latest version using `grunt`.

>
	$ grunt build



## Contributing

Please submit all pull requests the against master branch. If your unit test contains JavaScript patches or features, you should include relevant unit tests. Thanks!



## Authors

**Olivier Louvignes**

+ http://olouv.com
+ http://github.com/mgcrea



## Copyright and license

	The MIT License

	Copyright (c) 2012 Olivier Louvignes

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in
	all copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
	THE SOFTWARE.
