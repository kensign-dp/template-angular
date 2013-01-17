This project is a branch of HTML5 Boilerplate.

HTML5 Boilerplate is a professional front-end skeleton for building fast,
robust, and adaptable web apps or sites.

This branch is built to utilize [AngularJS](https://github.com/angular/angular.js) framework.

By default, the [Closure Compiler](https://developers.google.com/closure/compiler/) serves as the HTML 
compressor, CSS-linter, compressor and compiler, running SASS or LESS, based on the ant settings. 

## Quick start

Clone the git repo — `git clone https://github.com/kensign-dhap/dhap-template.git` - and checkout the tagged
release you'd like to use. The structure for this template is as follows:

	myApp/
		js/ *<- your main app code here.*        	
			lib/ *<- libraries you use here.*
		css/ *<- CSS/GSS/SASS etc.*
		build/ *<-Ant files, compilers, linting and compression.* see [ant-build-script](https://github.com/kensign-dhap/ant-build-script) for more info.
		intermediate/ *<- scratch directory for ant build *
		publish/ *<- the completed site generated from the ant build, compressed, linted and compiled. 

## Included Features

* [ant-build-script](https://github.com/kensign-dhap/ant-build-script) has been integrated. 
* [AngularJS](https://github.com/angular/angular.js) has been integrated. 