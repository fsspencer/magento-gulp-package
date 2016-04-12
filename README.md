# Gulp Package for Magento

This is a simple skin package for Magento 1 to let you implement the following features to make you able use a quicker and fancy method of coding.

  - Gulp
  - Sass
  - Css minifier
  - Js minifier
  - Image optimizer
  - Livereload
  - Bootstrap
  - Font Awesome


### Version
1.0.1

### Requirements

You need to install the following dependences on your local environment to make this work.

* [node.js] - evented I/O for the backend. Download the latest version on https://nodejs.org and install it
* [Gulp] - the streaming build system. Once you get NodeJS installed, make sure you can use the command "npm" on your terminal. Then install gulp


### Installation

Once you installed node.js, you need Gulp installed globally (maybe you need to use admin privileges with sudo):

```sh
$ npm install -g gulp
```

Let's create a new skin package on your magento project.
```sh
$ cd [magento-root-directory]
$ cd skin/frontend/[your-package-name]/default/
$ git clone [git-repo-url] .
$ npm install -d
```
All the dependences will be downloaded to a new directory called node_modules, which should be added to your .gitignore file (in case you are using git).

Download and install LiveReload Chrome Extension from the Chrome Web Store. 

Run the gulp watcher
```sh
$ gulp watch
```
Open your project url and make sure LiveReload is enabled. Then everythin should be working well.


