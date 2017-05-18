Adapted these directions: https://scotch.io/tutorials/setup-a-react-environment-using-webpack-and-babel

brew update

brew install yarn

yarn init

touch webpack.config.js

yarn add babel-loader babel-core babel-preset-es2015 babel-preset-react --dev

yarn add webpack webpack-dev-server path

touch .babelrc

mkdir client

touch client/index.js

touch client/index.html

yarn add html-webpack-plugin
