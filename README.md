## Getting started

## Install prerequisites

You need a Git client, the [Node.js](https://nodejs.org/), the [Bower package manager](https://bower.io/) and the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) to start the demo.
It is highly recommended to use the following versions:

* Node.js 6.10.2
* Bower 1.8.0
* Polymer CLI 1.2.0

### Git
Check if you have a Git client already installed:

```
git --version
```

If your OS can not recognize this command, install Git. For details please refer to [this page](http://git-scm.com).
When installing under Windows, please make sure you check the following option:

- [*] Use git from Windows command prompt

### Node.js

It is highly recommended to install the [Node Version Manager](https://github.com/creationix/nvm) which manages multiple active
Node.js versions on your machine. The latest windows version of nvm can be found [here](https://github.com/coreybutler/nvm-windows/releases/download/1.1.5/nvm-setup.zip).
Once [nvm](https://github.com/creationix/nvm) installed, install the Node.js and set it for use:

```
nvm install 6.10.2
nvm use 6.10.2
```

### Bower
Polymer still uses Bower as a package manager. Install it using npm (installed via [Node Version Manager](https://github.com/creationix/nvm)):
```
npm install -g bower
```

### Polymer CLI
Polymer CLI is the official command line tool for Polymer projects and Web Components. Install it using npm (installed via [Node Version Manager](https://github.com/creationix/nvm)):
```
npm install -g polymer-cli
```

## Start the demo

### Clone this repository

```
git clone https://github.com/pwa-polymer/number-input-element.git -b 1-start
```

### Install Bower dependencies

```
cd number-input-element
bower install
```

### View your element

```
$ polymer serve --open
```
