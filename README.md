# RxJS Boiler

Boilerplate for building RxJS applications in a Webpack environment

### Version
1.0.0

This uses RxJS version 5 - [https://github.com/ReactiveX/rxjs](https://github.com/ReactiveX/rxjs)

### Usage


### Installation

RxJS Boiler requires [Node.js](https://nodejs.org/) v4+ to run.

Install dependencies (Webpack, Babel, RxJS 5, jQuery)

```sh
$ npm install
```

### Compile
To compile all js to dist/app.bundle.js

```sh
$ webpack
```
To watch run
```sh
$ webpack -w
```

### Run
Install live-server globally
```sh
$ npm install live-server -g
```

```sh
$ npm start
```

Visit [http://localhost:8000](http://localhost:8000)

### Create a new git repo
You could [start writing code](#start-development) now and throw it all away when you're done.
If you'd rather preserve your work under source control, consider taking the following steps.

Initialize this project as a *local git repo* and make the first commit:
```shell
git init
git add .
git commit -m "Initial commit"
```

>Recover the deleted `.gitignore` from the QuickStart repository 
if you lost it in the _Delete non-essential files_ step.

Create a *remote repository* for this project on the service of your choice.

Grab its address (e.g. *`https://github.com/<my-org>/my-proj.git`*) and push the *local repo* to the *remote*.
```shell
git remote add origin <repo-address>
git push -u origin master
```
## Install npm packages

> See npm and nvm version notes above

Install the npm packages described in the `package.json` and verify that it works:

```shell
npm install
npm start
```

>Doesn't work in _Bash for Windows_ which does not support servers as of January, 2017.

The `npm start` command first compiles the application, 
then simultaneously re-compiles and runs the `lite-server`.
Both the compiler and the server watch for file changes.

Shut it down manually with `Ctrl-C`.

You're ready to write your application.
