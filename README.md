# Node Logging with winston

This tutorial demonstrates how to use the [winston logging library](https://github.com/winstonjs/winston) to create custom loggers in your Node.js application.

It also demonstrates how to customize transports and what you need to pay attention to when you **prepare your application for production use**.

<h3 align="center">Please help this repo with a ⭐️ if you find it useful! 😁</h3>

This repository is contains the code for the [Node winston logging tutorial on Youtube](https://www.youtube.com/watch?v=A5YiqaQbsyI)

[![Node winston logging tutorial](images/node-winston-logging-tutorial.png)](https://www.youtube.com/watch?v=A5YiqaQbsyI)

Please also check out my website at [jangoebel.com](https://jangoebel.com)

# How to run this application

Run

```
npm install
```

to install all dependencies

To see the output of the development logger run

```
npm run dev
```

The `dev` script automatically sets the `NODE_ENV` environment variable to `development`.

If the `NODE_ENV` environment variable is set to a different value than `development` (or not set at all), the production logger will be used.

To see the output of the production logger, just run

```
node index.js
```
