# Ionic + Angular template for Monaca

## What is this?

Monaca is a cloud-based Cordova development platform. With this template, you can easily get started with Ionic hybrid app.

## Getting started

1. Install Monaca & Ionic CLI

```
$ npm install -g monaca ionic
```

2. Create a project using this template

```
$ monaca create myapp --url https://github.com/monaca-templates/ionic-angular-tabbar/archive/master.zip
```

3. Use Ionic CLI to build (transpile) or serve

```
$ cd myapp
$ ionic serve
$ ionic build
```

4. Use Monaca CLI to connect to debugger or perform remote build

```
# Start remote build
$ monaca remote build --browser

# Connect to Monaca debugger
$ monaca debug & ionic serve
```
