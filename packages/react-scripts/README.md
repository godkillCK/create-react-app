# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.

# config

package.json
```json
"scripts": {
  "build_test": "react-scripts build --mode test",
  "build_prod": "react-scripts build --mode prod"
},
```

.env.test
```
REACT_APP_TEST=test
```

.env.prod
```
REACT_APP_TEST=prod
```

App.tsx
```
console.log(process.env.REACT_APP_TEST)

// build_test: test
// build_prod: prod
```
