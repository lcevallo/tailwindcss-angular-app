# TailwindcssAngularApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.10.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


https://jacobneterer.medium.com/angular-and-tailwindcss-2388fb6e0bab

https://github.com/Duomly/angular9-tailwind-bank-frontend

npx ng config projects.tailwindcss-angular-app.architect.build.builder @angular-builders/custom-webpack:browser
npx ng config projects.tailwindcss-angular-app.architect.build.options.customWebpackConfig.path webpack.config.js
npx ng config projects.tailwindcss-angular-app.architect.serve.builder @angular-builders/custom-webpack:dev-server
npx ng config projects.tailwindcss-angular-app.architect.test.builder @angular-builders/custom-webpack:browser
npx ng config projects.tailwindcss-angular-app.architect.test.options.customWebpackConfig.path webpack.config.js