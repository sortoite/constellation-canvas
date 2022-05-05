# Material App Pro - React Admin & Dashboard Template

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Prerequisites

You'll need to have Node 12.0.0 or up. We recommend upgrading to the LTS version of NodeJS available at [https://nodejs.org/](https://nodejs.org/). You can also use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to switch Node versions between different projects.

## Quick Start

### `npm start`

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

## React:

`All the necessary business logic should be encapsulated!!!`
For Business Logic encapsulation use:

- hook (preferable) - _It's not required to be a reused hook. Create a separate file for each hook._
- HOC - _It's not required to be a reused HOC. Create a separate file for each HOC._
- helper-functions - _It's not required to be a reused helper-function. Create a separate file, if a helper function is huge._

## Full component/page structure:

```
ComponentName.jsx       - component/page name
index.js                - file for export. Export component parts for quick access.
constants.js            - place constans here
helpers / helpers.js    - Create a folder, if there are lots of helpers. Create a file if they are few or they iclude some rows.
  index.js              - file for export
  useHelper.js          - hook
  helperFunc.js         - helper function
  withHelper.js         - HOC
components              - folder for auxiliary components, then the structure is the same.
  index.js
  AnyComponent
    AnyComponent.jsx
    types.js
    index.js
    ...
```
