# ex-react-tic-tac-toe

## Install

```
$ git clone https://github.com/mktktmr/ex-react-tic-tac-toe.git
$ cd ex-react-tic-tac-toe
$ npm install
```

## Execute on development environment

```
$ npm start
```

Running [webpack-dev-server](https://github.com/webpack/webpack-dev-server) on localhost:8080

Modify `webpack.config.dev.js` like below, if you'll like to change port.

`webpack.config.dev.js`

```javascript
  devServer: {
    contentBase: path.join(__dirname, "public"),
    port: 8081, // add this line
    inline: true,
    hot: true
  },
```
