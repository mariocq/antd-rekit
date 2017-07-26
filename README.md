# Antd-rekit

A production-ready toolkit for building scalable web applications with Ant Design and Rekit.

## Usage
you need to install dependencies and start the dev server:
```
npm install
npm start
```

It then starts three lightweight express servers by default:

 1. Wepback dev server: [http://localhost:6075](http://localhost:6075). This is the dev server your application is running on.
 2. Rekit portal: [http://localhost:6076](http://localhost:6076). The new Rekit dev tool shipped with Rekit 2.0.
 3. Build result test server: [http://localhost:6077](http://localhost:6077). This is the server for verifying the build result before deploying to production server.

To change the ports dev-servers running on, edit the `rekit` section in `package.json`:
```
{
  ...
  "rekit": {
    "devPort": 6075,
    "portalPort": 6076,
    "buildPort": 6077,
    ...
  }
  ...
}
```

## Key Features
 * It's production-ready but not a starter kit.
 * Zero additional configuration needed after creating an app.
 * Powerful Rekit portal to boost the efficiency of development.
 * Command line tools to manage actions, reducers, components and pages.
 * Embed build script and test server for the build result.
 * Use [Webpack 3](http://webpack.js.org) for bundling.
 * Use [Babel](https://babeljs.io/) for ES2015(ES6)+ support.
 * Use [React hot loader](http://gaearon.github.io/react-hot-loader/) for hot module replacement.
 * Use [Redux](http://redux.js.org/) for application state management.
 * Use [React-router](https://github.com/reactjs/react-router) for routing and it's configured with Redux reducer.
 * Use [Webpack dll plugin](http://webpack.github.io/docs/list-of-plugins.html#dllplugin) to improve dev-time build performance.
 * Use [Less](http://lesscss.org/) or [Sass](https://sass-lang.com/) as CSS transpilers.
 * Use [mocha](https://mochajs.org/), [enzyme](https://github.com/airbnb/enzyme) for testing.
 * Use [istanbul](https://github.com/gotwarlost/istanbul) for testing coverage report.
 * Use [eslint-config-airbnb](https://github.com/airbnb/javascript) for code style check.
 * Support [Redux dev tools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd).
 * Use Ant Design for UI solutions [ANT DESIGN](https://ant.design/index-cn).

## Documentation
[http://rekit.js.org](http://rekit.js.org)  
[https://ant.design/index-cn](https://ant.design/index-cn)

## License
MIT
