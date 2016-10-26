# Introduction
XYZ Admin -- is a fully responsive admin template based on Angular 2 and Bootstrap 3 framework.

## Steps
**Step 1: Understanding the configuration files and installing the packages we needed.**

We have 3 configuration files to setup our Angular 2 admin template app.
- package.json: contains all the dependencies needed for the app.
- tsconfig.json: setups the Typescript compiler to generate valid JavaScript
- systemjs.config.js: setups the SystemJS module loader

Before we begin creating our app, run the following command to get all of the packages we need
```
npm install 
```
This command will generate the node_modules folder containing all of your packages - it should look like the following

**Current app folder structure**
```
XYZ-Admin
  node_modules (folder)
  package.json
  systemjs.config.js
  tsconfig.json
```

**Step 2: Create app module**

In the root of your folder, create a folder named "app" and inside create a file named "app.module.ts"

Inside your app.module.ts add the following content

**app.module.ts**
```
import { NgModule }      from '@angular/core';
import { BrowserModule } from '@angular/platform-browser';

@NgModule({
imports: [ BrowserModule]
})

export class AppModule { }
```
**Current app folder structure**
```
XYZ-Admin
  app
    app.module.ts
  node_modules (folder)
  package.json
  systemjs.config.js
  tsconfig.json
```

## Architecture
!["Architecture"] (https://github.com/paulberesuita/XYZ-Admin/blob/master/README/xyz-%20admin-architecture.png "XYZ Admin")

## XYZ Admin Template - In-Progress
!["XYZ Admin Template"] (https://github.com/paulberesuita/XYZ-Admin/blob/master/README/xyz-admin-current.png "XYZ Admin")
