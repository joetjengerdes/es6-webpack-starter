# es6-webpack-starter

## Development
To run this starter kit in development mode, run the following commands:
```
npm install
npm run dev
```
Navigate your browser to ``localhost:3000``. Files are watched, so all changes are automatically built and the page will be refreshed automatically.

## Production
To run this starter kit in production mode, run the following commands:
```
npm install
npm run build
```
The bundled file is created in ``public/bundle.js``. It is minified and the comments are removed.

## Project structure
```
public/
    bundle.js
    index.html
src/
    styles/
        styles.scss 
    index.js
package.json
webpack.config.js
```
## Used libraries
The following libaries are included: 

- [Babel](https://babeljs.io/)
- [Webpack](http://webpack.github.io/)

## Licence
[MIT](LICENSE)
