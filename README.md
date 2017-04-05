# tasks-playground

[![Build Status](https://travis-ci.org/vsternbach/tasks-playground.svg?branch=master)](https://travis-ci.org/vsternbach/tasks-playground)
[![bitHound Overall Score](https://www.bithound.io/github/vsternbach/tasks-playground/badges/score.svg)](https://www.bithound.io/github/vsternbach/tasks-playground)

A sample tasks manager application to demonstrate the use of [angular-ts-decorators](https://github.com/vsternbach/angular-ts-decorators) library. It will serve as a playground for future porting of it to angular 4, react and maybe vue.js frameworks for self-learning and as an experiment to demonstrate the process of migration of angularjs applications to the most recent and popular frameworks. Future plans are to make application available as mobile and desktop application using native script/react-native and electron.

Some highlights of features and technologies used in the project:
- written in typescript 2.2 using angularjs 1.6 and component based architecture
- uses Google Tasks API with OAuth 2 authentication
- uses [Material Design Lite](https://getmdl.io/) for styling
- uses new async/await syntax in asynchronous code
- project based on [angularjs-typescript-webpack](https://github.com/vsternbach/angularjs-typescript-webpack) boilerplate
- has integration with Travis CI for testing(yet to be implemented) and deployment to firebase

You can see the working demo of the project at https://tasks-162620.firebaseapp.com

## Getting Started

To get you started you can simply clone the repository.

### Running the App during Development

`npm run start` will run dev build task with watch and serve the application on `http://localhost:3000/`.

### Building and running the App for Production

To build the application for production just run `npm build`, it creates dist directory that have the production optimized build.
