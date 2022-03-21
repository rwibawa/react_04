# react_04
React without CRA
* [React without CRA](https://dev.to/nikhilkumaran/don-t-use-create-react-app-how-you-can-set-up-your-own-reactjs-boilerplate-43l0)
* [Babel presets](https://babeljs.io/docs/en/presets)

## Setup
```sh
$ git init
$ git remote add origin git@github.com:rwibawa/react_04.git
$ git pull origin main

$ npm init
$ npm install react react-dom --save
$ npm install @babel/core @babel/preset-env @babel/preset-react --save-dev 
$ npm install webpack webpack-cli webpack-dev-server babel-loader css-loader style-loader html-webpack-plugin --save-dev 
```

## Create boilerplate
```sh
$ npm i fs-extra
$ mkdir bin/
$ vi bin/start.js

$ vi package.json
$ npm link

$ cd ..
$ rw-boilerplate myapp
```
