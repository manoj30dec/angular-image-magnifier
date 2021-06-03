# ImageMagnifier

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.2.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

use <image-magnifier [resultDistance]="10" [imagePath]="'../assets/hayden.jpg'" [imageWidth]="'250'" [imageHeight]="'338'"  [zoomLenseRange]="'80'"  style="float:left" ></image-magnifier> to produce image magnifire at any place.

Notes: following are some notes about properties

resultDistance = to give distance to result box from the preview image
imagePath = provide your image path here, it is recommended to use high resolution image here like 1200x1200.
imageWidth, imageHeight = provide preiview image dimensions here, it can be as per your web page design
zoomLenseRange = you can set zoom (lense size) range here. 


## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
