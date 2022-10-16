# react-scripts-less

---

### \_add less support to facebook/react-scripts

\_current react-scripts version:

```
react-scripts: 5.0.1
```

\_just replace react-scripts with react-scripts-less in package.json scripts block:

```json lines
"scripts": {
    "start": "react-scripts-less start",
    "build": "react-scripts-less build",
    "test": "react-scripts-less test",
}
```

\_also in your \*.d.ts for typescript project:

```js
/// <reference types="react-scripts-less" />
```

ps: add warnings ignoring for source map loader, which is helpful, for example, for ant.design less imports

---

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.
