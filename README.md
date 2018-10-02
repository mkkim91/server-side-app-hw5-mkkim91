## Simple starter Node.js server application for MGT-656/660 

This is a simple [Node.js](http://nodejs.org/)
application that we are using for the fifth
homework assignment in MGT-656/660 at
the Yale School of Management.

Please refer to the class website for the
instructions on how to submit this assignment. Here, you will 
find instructions on how to run the assignment code. Briefly, you will
need to clone this project in
[GitHub](http://www.github.com) and then
edit the `server.js` file. The `server.js` file
contains a tiny server-side application written
in JavaScript. I suspect most students in MGT-656
will want to use [Cloud9](http://c9.io) as your
code editor and "development environment"---a place
to run your application while you're working on it.

This repo contains a handful of files and the function of
each is described below.

* `server.js` - this is your server/application code. You can see at the top of that file a line like
    "`require('express');`". [Express](http://expressjs.com) is a "web application framework": a collection of code
    that helps you write web apps. Other popular web application frameworks include Ruby on Rails,
    Django, and Laravel. The [Express](http://expressjs.com) website documents how Express works
    and you'll likely "enjoy" reading it.
* `package.json` - this is Node's configuration file for your project.
    Inside you'll find information about the project, along with a list of dependencies (like Express) that get installed into a `node_modules/` directory when you run `npm install`.
* `package-lock.json` - this file describes the dependencies of your dependencies. For example,
    it shows precisely which dependencies Express has. We use this file to ensure that
    when I run the code on my machine, it is *exactly* the same experience as you running
    the code on your machine.
* `.gitignore` - this tells Git which files and folders to ignore -- for example,
    you don't want to keep `node_modules/` under version control with git because
    the files therein are created automatically when you run `npm install`.
* `Procfile` - this is how you tell Heroku how to run your code. You shouldn't need to mess with this one.
* `README.md` - this file :). If you look at the file, you can see it is written
   in [markdown](https://en.wikipedia.org/wiki/Markdown) format, which is a popular
   format for documentation.
