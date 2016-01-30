# Setup

## 1) Install NodeJS & NPM

https://nodejs.org/en/download/

## 2) Install JSPM

    $ sudo npm install -g jspm

## 3) Install Ruby & SASS

http://sass-lang.com/install

## 4) Install Other Dependencies

    $ npm install

(This will also trigger `jspm install`)

## 5) Start Local Server & File Watcher

    $ npm start

This will start a local webserver on http://127.0.0.1:8000

# Documentation Links
## Frontend

- JavaScript: https://github.com/getify/You-Dont-Know-JS/
- React Docs: https://facebook.github.io/react/docs/getting-started.html
- React Style Guide: https://github.com/Khan/style-guides/blob/master/style/react.md
- JSX: https://facebook.github.io/react/docs/jsx-in-depth.html

## Tooling

- ES6 Module System: https://github.com/systemjs/systemjs/blob/master/docs/es6-modules-overview.md
- Babel: https://babeljs.io
- System.js: https://github.com/systemjs/systemjs
- JSPM: http://jspm.io
- NPM: https://docs.npmjs.com

## Testing

- Jasmine Docs: http://jasmine.github.io/2.3/introduction.html
- Jasmine Cheatsheet: http://www.cheatography.com/citguy/cheat-sheets/jasmine-js-testing/
- Karma Docs: http://karma-runner.github.io
- React Test Utils: https://facebook.github.io/react/docs/test-utils.html

# Remarks / things to watch out for

- Code reloading sometimes takes some seconds
- Transpile errors sometimes hard to spot in terminal
- To kill old server ("port already taken") do `killall node`
