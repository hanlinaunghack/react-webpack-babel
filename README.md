[![Build Status](https://travis-ci.org/ddubson/react-webpack-babel.svg?branch=master)](https://travis-ci.org/ddubson/react-webpack-babel)
[![bitHound Dependencies](https://www.bithound.io/github/ddubson/react-webpack-babel/badges/dependencies.svg)](https://www.bithound.io/github/ddubson/react-webpack-babel/master/dependencies/npm)
[![bitHound Dev Dependencies](https://www.bithound.io/github/ddubson/react-webpack-babel/badges/devDependencies.svg)](https://www.bithound.io/github/ddubson/react-webpack-babel/master/dependencies/npm)

# React / Babel / Webpack boilerplate project

This project serves to jumpstart anyone who wants to have React up and running in no time with all the Webpack and Babel configurations pre-built. 
Now with Redux!


## Building and Running the project

Here's what you do to get this up and running on your machine:

```
git clone https://github.com/ddubson/react-webpack-babel
cd react-webpack-babel
npm install
npm run start
```

This project has webpack and babel configured from scratch so you have full control of customizations to add or remove should you choose to.

## Commands available

### Building for production

Building the project for production use:

`npm run dist`

uses babel to transpile all the resources in the project into the `dist/` directory.

### Run locally

Run the project on your local machine

`npm run start`

uses webpack-dev-server to run the React app on your machine.

### Executing Tests

This project uses:

```
Enzyme -> React Test Utility Framework (AirBnB)
Jest -> Test Runner and Spec Framework (Facebook)
```

The test files (or `specs`) are stored in `__tests__/` directory. The full test suite can be run by:

`npm run test`

### Running syntax linter - ESLint

To verify syntax, run:

`npm run lint`

This command checks the `src` and `__tests__` directories.

---
