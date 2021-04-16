# Building Trello with Drag and Drop

## Introduction
Trello Clone was built with using React and Typescript. To simplify the process of creating a react app, we will use create-react-app. It is a tool that will generate
the file structure and automatically create all the settings files for our project. If you’ve
worked with React before - you might be familiar with it but if you haven’t yet - no worries, You just have to follow the
steps in this project exactly to get it up and running.

## Prerequisites
- First of all, you need to know how to use the command line. On Mac, you can
use Terminal.app. On Windows I recommend using Cygwin17 or
Cmder
- You will need a code editor with Typescript support. I recommend using VSCode, it
supports Typescript out of the box.
- Make sure you have Node 10.16.0 or later
- You also need node package managers. This project was built using Yarn. You can 
 remove the yarn.lock files, remove if you want to use npm to install dependencies. 


## Get started

- Install yarn (optional)
```sh  
npm install --global yarn
```

```sh
 yarn create-react-app --template typescript trello-clone

```

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More


To learn React, check out the [React documentation](https://reactjs.org/).
