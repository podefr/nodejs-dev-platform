#nodejs-dev-platform

How to use node.js as a web development platform?

Node.js is fantastic when it comes to running JavaScript on the server side, but with powerful tools like npm, its module system, browserify and other tools, it can also become a powerful development platform to write and build applications, frameworks or libraires. This project shows a completely integrated workflow that allows you to simply develop, test and deliver your JavaScript for both the client and the server, whether it's a final application or something that other people will reuse, such as a library or a framework.

## Writing web applications, frameworks or libraries, what is required?

- Module management for dependencies, either own dependencies or third-party dependencies.
- Run tests, whether they are unit tests, integration tests, performance tests, you name it.
- Build your application, framework or library, when you're ready to package it.
- Package your application, framework or library, when you want to deliver it.
- Distribute your application, framework or library.

## Let's start with a simple layout for structure your project.

First, we need to separate the code that we write and the code that we deliver. Nowadays, as the JavaScript that we write gets more complex, we want to separate them so that we can apply transformations to the code that is delivered, such as:

 - Concatenation and minification
 - Transpilation, like coffeescript to JS or ES6 to ES5.
 - Optimisation
 - Compilation for security
 - Packaging for delivering parts of the code separately

So we're going to create a `src` directory, and a `build` directory.

```
    |- src/
    |- build/
```

## Managing dependencies of your application.

Dependency management with npm is as easy as listing dependencies in the `package.json`.

### LICENSE

MIT

