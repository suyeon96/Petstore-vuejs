# petstore-vuejs

Mini web project for study vue.js  
(Reference Book : Vue.js 코딩 공작소)

## Prepare the environment

### 1. Install Node.js & npm

Node.js : http://nodejs.org/en/download  
NVM : https://github.com/creationix/nvm

**for MacOS**
``` bash
# Homebrew
$ brew install node

# MacPort
$ sudo port install nodejs
```

**for Linux**
``` bash
# ubuntu
$ sudo apt-get install nodejs

# pedora
$ yum install nodejs
```

**check**
``` bash
$ node -v
$ npm -v
```

### 3. Create Vue-CLI Application

``` bash
# Install vue-cli
$ npm install -g vue-cli

# Create project
$ vue init webpack petstore  # vue init <template-name> <project-name>
$ cd petstore
```

### 4. Install Vuex

``` bash
$ npm install vuex
```


## Dev Build

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

