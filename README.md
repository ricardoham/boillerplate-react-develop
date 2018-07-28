# Boilerplate React
This project is configured with Webpack v4.

### Getting Started
All that you need is:

```
clone this repo,
run npm install

put your code to rock! 🎸

```

### Some of modules include in webpack:
```javascript
  module: {
    rules: [
      {
        test:/\.js$/,
        exclude: /node_modules/,
        loader: 'babel-loader',
        query: {
          presets: ['react', 'es2015', 'stage-2'],
        }
      },
      {
        test: /\.css$/,
        use: [
          'style-loader',
          'css-loader',
        ]
      },
      {
        test: /\.(png|svg|jpg|gif)$/,
        use: ['file-loader'],
      }
    ]
  },
```
### Start scripts:
```json
  "scripts": {
    "start": "webpack-dev-server --progress --colors --open --hot"
  },

```

## License

This project is licensed under the MIT License.