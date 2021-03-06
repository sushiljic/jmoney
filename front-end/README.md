# JMoney front-end

This is the Angular 2 based front-end. It runs with a standalone dev server that proxies requests to the back-end.

## Preparations

`npm install -g angular-cli`

and

`npm install`

## Development server

Run `npm start` or `ng serve --proxy proxy.config.json` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `npm test` or `ng test --browsers=Chrome` to execute the unit tests via [Karma](https://karma-runner.github.io).

Coverage report: `ng test -w=false -cc`. Results will be in `coverage` folder.

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the `angular-cli` use `ng help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
