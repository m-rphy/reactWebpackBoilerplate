# reactWebpackBoilerplate


NOTE: If you’re going to use version control, now would be a good time to git init and add a .gitignore file.

install node modules with npm install

Dependencies
    react 
    react-dom

    DevDependencies
    webpack - - - - - - - -> to bundle and compile our code
    webpack-cli - - - - - -> to interact with our code
    webpack-dev-server- - -> provides us with a live-reloading development server
    bable-loader- - - - - -> tells webpack to run our code through babel
    @babel/core - - - - - -> core babel package which will use @babel/preset-env
    @babel/preset-env - - -> transpile our modern ES6+ JavaScript down
    @babel/preset-react - -> compiles our JSX files to JavaScript

    (not necessary, but...)
    html-sebpack-plugin - -> allows us to keep our source files 
    separate from our distribution files and auto-generates our 
    index.html file with a script tag pointing to our bundled JavaScript


The File Structure of our Code is...


    / (reactBoilerPlate)
    ├── node_modules/...
    ├── src\n
    │   ├── components/\n
    │   │   └── App.js
    │   ├── index.html
    │   └── index.js
    ├── .babelrc
    ├── package-lock.json
    ├── package.json
    └── webpack.config.js 

TODO 

- Add more webpack loaders to handle other types of files (CSS, SASS, images, fonts etc.)

- Install and configure code quality tooling such as ESLint and/or Prettier

- Add dotenv and environment variables files

- Split webpack config into development, production and common configs

- Install and configure a testing framework, e.g. Jest, Mocha etc.
