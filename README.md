# MyAngularElectronAppDemo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.3.


## Tutorials
https://medium.com/@yannmjl/how-to-build-native-cross-platform-desktop-apps-with-angular-electron-bd1d6e3919b2

There was an issue runing ```npm run electron-build```. This ended up being cause by using nodejs 11.x. Using the link below install "n" to install and switch between nodejs versions. See https://github.com/angular/angular-cli/issues/15490 and see "n" at  https://www.surrealcms.com/blog/how-to-upgrade-or-downgrade-nodejs-using-npm.html

There is another issue with ```npm run electron-build``` or ```npm run electron .```. When electron opens the window is blank. The console shows an error for unknow mime-type which is required for script tags. to fix change the target in th etsconfig.json file to es5. See this link: https://github.com/angular/angular/issues/30835



## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
