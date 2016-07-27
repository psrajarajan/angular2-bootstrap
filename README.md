!!! Deprecated !!!
========================
Please use the official angular-ui project: https://github.com/ng-bootstrap/ng-bootstrap




In case you still want to run this old code:
========================

Project started from: https://github.com/mgechev/angular2-seed  
  
**Demo available here:** http://mlaval.github.io/angular2-bootstrap/  

## Development

### Preparing your environment

- install Gulp and TSD globally: `npm install -g gulp tsd`
- install local npm modules: `npm install`

### Running scripts
<!---
For jshint validation:

- run `gulp checkstyle`
-->
To build the project:
- run `gulp build.dev` or `gulp build.prod` to build it into **dist** folder

To start the demo application:
- run `gulp serve.dev` or `gulp.serve.prod` to build it and start a webserver which watches source files at http://localhost:5555  

To run unit tests and watch source files:
- run `gulp test`

To run end to end tests:
- run `gulp e2e`

To clean all files created during builds:
- run `gulp clean`
