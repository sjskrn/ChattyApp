Chatty App
=====================

A Lighthouse Labs project with focus on React and Web Sockets. 

### Usage

Clone the ChattyApp  

```
git clone git@github.com:sjskrn/ChattyApp.git
cd ChattyApp
```

Install the dependencies and start the server.

```
npm install
npm start
open http://localhost:3000 in chrome
```

### Static Files

You can store static files like images, fonts, etc in the `build` folder.

For example, if you copy a file called my_image.png into the build folder you can access it using `http://localhost:3000/build/my_image.png`.

### Dependencies

* React
* Webpack
* [babel-loader](https://github.com/babel/babel-loader)
* [webpack-dev-server](https://github.com/webpack/webpack-dev-server)
