# Template_v1
This template is a set up of a project using webpack and babel to create a simple web app.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Do ensure that you have Node.js installed on your machine.


### Installing

Follow these steps to help you get started.

**1. Install dependencies**

Open the project folder in your terminal and run the following command
```
npm install
```

**2. Run the project on localhost**

Once the dependencies have been installed, run the following command. Once webpack finished compiling the files, head over to http://localhost:8888 on your browser.

```
npm run start
```

Now you can work on your project! :) :v:

## Directory Structure
This project contains a development folder and production folder.

### Development folder
The src folder is where you should edit your files. This folder contains static files and files for javascript and styling.

#### Static files
This folder includes your index.html and this is where you store your data files and images.
```
src/public
```

#### Javascript files

The following folder should consist of all the necessary js files that you need.

```
src/app/*.js
```

The following js file has been created for you to help you get started immediately!
```
src/app/index.js
```

#### Styling your website

In this project, we will be using SASS to style our website. The following folder should consist of all the necessary scss files that you need.

```
src/style/*.scss
```

The following files have been created for you to help you get started!
```
src/style/app.scss //global styling
src/style/layout1.scss
```

### Production folder
This folder should contain your production build. Read the Deployment section to find out how to build a production build.
```
/dist
```

## Deployment

Follow these steps to host your project on Firebase! :fire:

If you are using other hosting platforms to host your website. Follow step 1 before deploying them.

**1. Create production build**

Run the following command to bundle your files into bundle.js and this will be automatically generated into your production folder.
```
npm run build
````
Copy your index.html, data files and images into the production folder.

**2. Deploy onto Firebase**

Ensure that you have initialised your firebase files before conducting. If you have not, do refer to this website https://firebase.google.com/docs/hosting/quickstart

Once you've initialised your Firebase project, run the following command. All files in your production folder will be deployed onto your Firebase project.

```
firebase deploy
```

## Authors

* **Karisse Khoo**

## Version

*Last updated: 23 June 2019*

## Acknowledgments

* https://scotch.io/tutorials/setting-up-webpack-for-any-project
* https://github.com/webpack-contrib/mini-css-extract-plugin
