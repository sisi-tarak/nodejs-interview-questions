# Node.js Interview Questions & Answers

> Click ⭐ if you like the project. Follow me [@sisi_tarakk](https://www.instagram.com/sisi_tarakk) on Instagram and [@sisitarak](https://www.linkedin.com/in/sisitarak) on LinkedIn for more.

> Pull Requests are highly recommended and appreciated. 🙌

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

#### 🟢 Basic Level

| No. | Questions |
| --- | --------- |
| 1 | [What is Node.js?](#1-what-is-nodejs) |
| 2 | [What is the V8 engine?](#2-what-is-the-v8-engine) |
| 3 | [What are the key features of Node.js?](#3-what-are-the-key-features-of-nodejs) |
| 4 | [What is the difference between Node.js and JavaScript in the browser?](#4-what-is-the-difference-between-nodejs-and-javascript-in-the-browser) |
| 5 | [What is npm? What is the role of package.json?](#5-what-is-npm-what-is-the-role-of-packagejson) |
| 6 | [What is the difference between npm and npx?](#6-what-is-the-difference-between-npm-and-npx) |
| 7 | [What is a module in Node.js?](#7-what-is-a-module-in-nodejs) |
| 8 | [What is the difference between CommonJS and ES Modules in Node.js?](#8-what-is-the-difference-between-commonjs-and-es-modules-in-nodejs) |
| 9 | [What are the types of modules in Node.js?](#9-what-are-the-types-of-modules-in-nodejs) |
| 10 | [What is the global object in Node.js?](#10-what-is-the-global-object-in-nodejs) |
| 11 | [What is process object in Node.js?](#11-what-is-process-object-in-nodejs) |
| 12 | [What is the difference between synchronous and asynchronous code?](#12-what-is-the-difference-between-synchronous-and-asynchronous-code) |
| 13 | [What are callbacks in Node.js?](#13-what-are-callbacks-in-nodejs) |
| 14 | [What is callback hell? How do you avoid it?](#14-what-is-callback-hell-how-do-you-avoid-it) |
| 15 | [What are Promises in Node.js?](#15-what-are-promises-in-nodejs) |
| 16 | [What is async/await in Node.js?](#16-what-is-asyncawait-in-nodejs) |
| 17 | [What is the fs module in Node.js?](#17-what-is-the-fs-module-in-nodejs) |
| 18 | [What is the path module in Node.js?](#18-what-is-the-path-module-in-nodejs) |
| 19 | [What is the os module in Node.js?](#19-what-is-the-os-module-in-nodejs) |
| 20 | [What is the http module in Node.js?](#20-what-is-the-http-module-in-nodejs) |
| 21 | [What is the difference between __dirname and __filename?](#21-what-is-the-difference-between-__dirname-and-__filename) |
| 22 | [What is REPL in Node.js?](#22-what-is-repl-in-nodejs) |
| 23 | [What is the difference between dependencies and devDependencies?](#23-what-is-the-difference-between-dependencies-and-devdependencies) |
| 24 | [What is package-lock.json? Why is it important?](#24-what-is-package-lockjson-why-is-it-important) |
| 25 | [What are environment variables? How do you use them in Node.js?](#25-what-are-environment-variables-how-do-you-use-them-in-nodejs) |

#### 🟡 Medium Level — Event Loop & Core Concepts

| No. | Questions |
| --- | --------- |
| 26 | [What is the Event Loop in Node.js?](#26-what-is-the-event-loop-in-nodejs) |
| 27 | [What are the phases of the Event Loop?](#27-what-are-the-phases-of-the-event-loop) |
| 28 | [What is the difference between process.nextTick() and setImmediate()?](#28-what-is-the-difference-between-processnexttick-and-setimmediate) |
| 29 | [What is libuv in Node.js?](#29-what-is-libuv-in-nodejs) |
| 30 | [What is the Thread Pool in Node.js?](#30-what-is-the-thread-pool-in-nodejs) |
| 31 | [What are Streams in Node.js?](#31-what-are-streams-in-nodejs) |
| 32 | [What are the types of Streams in Node.js?](#32-what-are-the-types-of-streams-in-nodejs) |
| 33 | [What is piping in Node.js streams?](#33-what-is-piping-in-nodejs-streams) |
| 34 | [What are Buffers in Node.js?](#34-what-are-buffers-in-nodejs) |
| 35 | [What is the EventEmitter class in Node.js?](#35-what-is-the-eventemitter-class-in-nodejs) |
| 36 | [What is the difference between EventEmitter and Streams?](#36-what-is-the-difference-between-eventemitter-and-streams) |
| 37 | [What is clustering in Node.js?](#37-what-is-clustering-in-nodejs) |
| 38 | [What is the Worker Threads module in Node.js?](#38-what-is-the-worker-threads-module-in-nodejs) |
| 39 | [What is the difference between cluster and worker_threads?](#39-what-is-the-difference-between-cluster-and-worker_threads) |
| 40 | [How does Node.js handle concurrency if it is single-threaded?](#40-how-does-nodejs-handle-concurrency-if-it-is-single-threaded) |

#### 🟡 Medium Level — Express.js

| No. | Questions |
| --- | --------- |
| 41 | [What is Express.js?](#41-what-is-expressjs) |
| 42 | [What is middleware in Express.js?](#42-what-is-middleware-in-expressjs) |
| 43 | [What are the types of middleware in Express.js?](#43-what-are-the-types-of-middleware-in-expressjs) |
| 44 | [What is the difference between app.use() and app.get()?](#44-what-is-the-difference-between-appuse-and-appget) |
| 45 | [What is the next() function in Express middleware?](#45-what-is-the-next-function-in-express-middleware) |
| 46 | [How do you handle errors in Express.js?](#46-how-do-you-handle-errors-in-expressjs) |
| 47 | [What is the difference between req.params, req.query, and req.body?](#47-what-is-the-difference-between-reqparams-reqquery-and-reqbody) |
| 48 | [What is Express Router?](#48-what-is-express-router) |
| 49 | [How do you serve static files in Express.js?](#49-how-do-you-serve-static-files-in-expressjs) |
| 50 | [What is CORS? How do you handle it in Node.js?](#50-what-is-cors-how-do-you-handle-it-in-nodejs) |

#### 🟡 Medium Level — Database & APIs

| No. | Questions |
| --- | --------- |
| 51 | [How do you connect Node.js to MongoDB?](#51-how-do-you-connect-nodejs-to-mongodb) |
| 52 | [What is Mongoose? What are its advantages?](#52-what-is-mongoose-what-are-its-advantages) |
| 53 | [What is the difference between SQL and NoSQL databases?](#53-what-is-the-difference-between-sql-and-nosql-databases) |
| 54 | [How do you connect Node.js to a SQL database?](#54-how-do-you-connect-nodejs-to-a-sql-database) |
| 55 | [What is an ORM? Name popular ORMs for Node.js](#55-what-is-an-orm-name-popular-orms-for-nodejs) |
| 56 | [What is REST API? How do you build one in Node.js?](#56-what-is-rest-api-how-do-you-build-one-in-nodejs) |
| 57 | [What are HTTP methods and their purposes?](#57-what-are-http-methods-and-their-purposes) |
| 58 | [What are HTTP status codes? List important ones](#58-what-are-http-status-codes-list-important-ones) |
| 59 | [What is GraphQL? How is it different from REST?](#59-what-is-graphql-how-is-it-different-from-rest) |
| 60 | [What is pagination? How do you implement it in Node.js?](#60-what-is-pagination-how-do-you-implement-it-in-nodejs) |

#### 🔴 Advanced Level — Authentication & Security

| No. | Questions |
| --- | --------- |
| 61 | [What is JWT? How does it work?](#61-what-is-jwt-how-does-it-work) |
| 62 | [What is the difference between authentication and authorization?](#62-what-is-the-difference-between-authentication-and-authorization) |
| 63 | [How do you implement JWT authentication in Node.js?](#63-how-do-you-implement-jwt-authentication-in-nodejs) |
| 64 | [What is bcrypt? Why do you hash passwords?](#64-what-is-bcrypt-why-do-you-hash-passwords) |
| 65 | [What is OAuth 2.0?](#65-what-is-oauth-20) |
| 66 | [What is helmet.js? What security headers does it set?](#66-what-is-helmetjs-what-security-headers-does-it-set) |
| 67 | [What is rate limiting? How do you implement it?](#67-what-is-rate-limiting-how-do-you-implement-it) |
| 68 | [What is SQL Injection? How do you prevent it in Node.js?](#68-what-is-sql-injection-how-do-you-prevent-it-in-nodejs) |
| 69 | [What is CSRF? How do you prevent it?](#69-what-is-csrf-how-do-you-prevent-it) |

#### 🔴 Advanced Level — Performance & Architecture

| No. | Questions |
| --- | --------- |
| 70 | [What is caching? How do you implement it with Redis in Node.js?](#70-what-is-caching-how-do-you-implement-it-with-redis-in-nodejs) |
| 71 | [What is a message queue? Name popular ones used with Node.js](#71-what-is-a-message-queue-name-popular-ones-used-with-nodejs) |
| 72 | [What is WebSocket? How do you implement real-time communication in Node.js?](#72-what-is-websocket-how-do-you-implement-real-time-communication-in-nodejs) |
| 73 | [What is Socket.IO?](#73-what-is-socketio) |
| 74 | [What is the difference between WebSocket and HTTP?](#74-what-is-the-difference-between-websocket-and-http) |
| 75 | [How do you handle file uploads in Node.js?](#75-how-do-you-handle-file-uploads-in-nodejs) |
| 76 | [What is PM2? Why is it used in production?](#76-what-is-pm2-why-is-it-used-in-production) |
| 77 | [How do you debug a Node.js application?](#77-how-do-you-debug-a-nodejs-application) |
| 78 | [How do you handle memory leaks in Node.js?](#78-how-do-you-handle-memory-leaks-in-nodejs) |
| 79 | [What is microservices architecture? How does Node.js fit?](#79-what-is-microservices-architecture-how-does-nodejs-fit) |
| 80 | [What is serverless computing? How does Node.js work in serverless?](#80-what-is-serverless-computing-how-does-nodejs-work-in-serverless) |

#### 🔴 Advanced Level — Testing & Best Practices

| No. | Questions |
| --- | --------- |
| 81 | [How do you test a Node.js application?](#81-how-do-you-test-a-nodejs-application) |
| 82 | [What is Jest? How do you use it for Node.js testing?](#82-what-is-jest-how-do-you-use-it-for-nodejs-testing) |
| 83 | [What is Supertest? How do you test Express APIs?](#83-what-is-supertest-how-do-you-test-express-apis) |
| 84 | [What is mocking in testing?](#84-what-is-mocking-in-testing) |
| 85 | [What is the 12-Factor App methodology? How does it apply to Node.js?](#85-what-is-the-12-factor-app-methodology-how-does-it-apply-to-nodejs) |

#### 🎯 Scenario & Conceptual Questions (MNC Favourites)

| No. | Questions |
| --- | --------- |
| 86 | [Why is Node.js not suitable for CPU-intensive tasks?](#86-why-is-nodejs-not-suitable-for-cpu-intensive-tasks) |
| 87 | [What happens when you block the event loop?](#87-what-happens-when-you-block-the-event-loop) |
| 88 | [How do you scale a Node.js application?](#88-how-do-you-scale-a-nodejs-application) |
| 89 | [What is graceful shutdown in Node.js?](#89-what-is-graceful-shutdown-in-nodejs) |
| 90 | [How do you structure a large Node.js project?](#90-how-do-you-structure-a-large-nodejs-project) |
| 91 | [What is the difference between monolithic and microservices architecture?](#91-what-is-the-difference-between-monolithic-and-microservices-architecture) |
| 92 | [What is dependency injection in Node.js?](#92-what-is-dependency-injection-in-nodejs) |
| 93 | [What is the difference between spawn, exec, execFile, and fork in child_process?](#93-what-is-the-difference-between-spawn-exec-execfile-and-fork-in-child_process) |
| 94 | [What is the difference between readFile and createReadStream?](#94-what-is-the-difference-between-readfile-and-createreadstream) |
| 95 | [How do you manage multiple async operations in Node.js?](#95-how-do-you-manage-multiple-async-operations-in-nodejs) |
| 96 | [What is NestJS? How is it different from Express.js?](#96-what-is-nestjs-how-is-it-different-from-expressjs) |
| 97 | [What is Fastify? How does it compare to Express?](#97-what-is-fastify-how-does-it-compare-to-express) |
| 98 | [What are common Node.js security best practices?](#98-what-are-common-nodejs-security-best-practices) |
| 99 | [What is the difference between setTimeout, setInterval, and setImmediate?](#99-what-is-the-difference-between-settimeout-setinterval-and-setimmediate) |
| 100 | [What are the new features in recent Node.js versions (v20/v22)?](#100-what-are-the-new-features-in-recent-nodejs-versions-v20v22) |

</details>

---

<br>

## 🟢 Basic Level

<br>

### 1. What is Node.js?

Node.js is an **open-source, cross-platform JavaScript runtime environment** that allows you to execute JavaScript code outside the browser — on the server side. It is built on **Chrome's V8 JavaScript engine** and designed for building scalable, fast, and efficient network applications.

Node.js was created by **Ryan Dahl** in **2009** and is maintained by the **OpenJS Foundation**.

**Why Node.js is popular:**
- Uses JavaScript — one language for both frontend and backend
- Non-blocking, event-driven I/O — handles thousands of concurrent connections efficiently
- Huge ecosystem — over 2 million packages on npm
- Used by companies like Netflix, LinkedIn, Uber, PayPal, and NASA

```js
// simplest Node.js HTTP server
const http = require('http');

const server = http.createServer((req, res) => {
  res.writeHead(200, { 'Content-Type': 'text/plain' });
  res.end('Hello from Node.js!');
});

server.listen(3000, () => console.log('Server running on http://localhost:3000'));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 2. What is the V8 engine?

V8 is an **open-source, high-performance JavaScript engine** developed by Google, written in C++. It is used in both Google Chrome browser and Node.js.

**How V8 works:**
- Parses JavaScript source code into an **Abstract Syntax Tree (AST)**
- Compiles AST to machine code using the **JIT (Just-In-Time) compiler**
- Executes machine code directly — no interpreter needed
- Continuously optimizes hot code paths using **TurboFan** (optimizing compiler)

V8 also manages **Garbage Collection** — automatically freeing memory that is no longer in use (using Mark-and-Sweep algorithm).

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 3. What are the key features of Node.js?

| Feature | Description |
| ------- | ----------- |
| **Asynchronous & Non-blocking** | I/O operations don't block the thread; callbacks/promises are used |
| **Single-threaded** | Uses one thread with an event loop for concurrency |
| **Event-driven** | Uses events and callbacks to handle operations |
| **Fast execution** | Powered by Chrome's V8 engine — compiles JS to machine code |
| **Scalable** | Handles thousands of concurrent connections with minimal resources |
| **Cross-platform** | Runs on Windows, macOS, Linux |
| **Rich ecosystem** | npm has 2M+ packages |
| **Streams** | Efficient handling of large data via readable/writable streams |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 4. What is the difference between Node.js and JavaScript in the browser?

| Feature | Node.js | Browser JavaScript |
| ------- | ------- | ------------------ |
| Environment | Server-side | Client-side |
| Global object | `global` | `window` |
| DOM access |   No DOM |  Yes |
| File system access |  Yes (`fs` module) |   No |
| Networking |  Full TCP/UDP | Limited (fetch/XHR) |
| Module system | CommonJS (`require`) / ESM | ESM (`import`) |
| APIs | `http`, `fs`, `os`, `path`, etc. | `document`, `window`, `localStorage` |
| Purpose | Build servers, CLIs, tools | Build UIs, interact with browser |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 5. What is npm? What is the role of package.json?

**npm (Node Package Manager)** is the default package manager for Node.js. It allows you to install, share, and manage external libraries and tools.

**package.json** is the **manifest file** of a Node.js project. It stores metadata and configuration:

```json
{
  "name": "my-app",
  "version": "1.0.0",
  "description": "My Node.js application",
  "main": "index.js",
  "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js",
    "test": "jest"
  },
  "dependencies": {
    "express": "^4.18.2",
    "mongoose": "^7.0.0"
  },
  "devDependencies": {
    "nodemon": "^3.0.0",
    "jest": "^29.0.0"
  },
  "engines": {
    "node": ">=18.0.0"
  }
}
```

**Common npm commands:**

```bash
npm init -y              # create package.json
npm install express      # install and add to dependencies
npm install jest --save-dev  # install and add to devDependencies
npm install              # install all dependencies from package.json
npm uninstall express    # remove a package
npm update               # update all packages
npm run dev              # run a script
npm audit                # check for security vulnerabilities
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 6. What is the difference between npm and npx?

| Feature | npm | npx |
| ------- | --- | --- |
| Full form | Node Package Manager | Node Package Execute |
| Purpose | Install and manage packages | Execute packages without installing globally |
| Global install needed? | Yes (for CLI tools) |   No — downloads and runs on the fly |
| Use case | Managing dependencies | Running one-time CLI commands |

```bash
# npm — installs globally first, then run
npm install -g create-react-app
create-react-app my-app

# npx — runs directly without global install
npx create-react-app my-app

# npx is useful for:
npx nodemon index.js        # run without global install
npx prisma generate         # run CLI tools
npx ts-node script.ts       # run TypeScript directly
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 7. What is a module in Node.js?

A module is a **reusable block of code** encapsulated in its own file. Node.js follows the module pattern — each file is treated as a separate module with its own scope. Variables/functions are not globally accessible unless explicitly exported.

```js
// math.js — creating a module
const add = (a, b) => a + b;
const subtract = (a, b) => a - b;
const PI = 3.14159;

// Export
module.exports = { add, subtract, PI };

// app.js — using the module
const { add, subtract, PI } = require('./math');

console.log(add(5, 3));      // 8
console.log(subtract(10, 4)); // 6
console.log(PI);              // 3.14159
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 8. What is the difference between CommonJS and ES Modules in Node.js?

| Feature | CommonJS (CJS) | ES Modules (ESM) |
| ------- | -------------- | ---------------- |
| Syntax | `require()` / `module.exports` | `import` / `export` |
| Loading | Synchronous | Asynchronous |
| File extension | `.js` (default) | `.mjs` or `"type": "module"` in package.json |
| Tree shaking |   Not supported |  Supported |
| Top-level await |   Not supported |  Supported |
| Default in Node.js |  Yes (legacy) | Modern standard |
| `__dirname` / `__filename` |  Available |   Not available (use `import.meta.url`) |

```js
// CommonJS
const express = require('express');
module.exports = { handler };

// ES Modules
import express from 'express';
export { handler };
export default router;
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 9. What are the types of modules in Node.js?

Node.js has three types of modules:

**1. Core (Built-in) Modules** — shipped with Node.js, no installation needed:

```js
const fs = require('fs');       // file system
const http = require('http');   // HTTP server
const path = require('path');   // file paths
const os = require('os');       // operating system info
const crypto = require('crypto'); // encryption
const events = require('events'); // EventEmitter
```

**2. Local Modules** — files you create in your project:

```js
const userService = require('./services/userService');
```

**3. Third-party Modules** — installed via npm:

```js
const express = require('express');
const mongoose = require('mongoose');
const jwt = require('jsonwebtoken');
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 10. What is the global object in Node.js?

In Node.js, `global` is the **global namespace object** — similar to `window` in the browser. Variables attached to it are accessible anywhere in the app.

```js
// Commonly available globals (no require needed):
console.log('Hello');          // global.console
setTimeout(() => {}, 1000);    // global.setTimeout
setInterval(() => {}, 1000);   // global.setInterval
clearTimeout(id);              // global.clearTimeout
process.env.PORT;              // global.process
__dirname;                     // current directory (CJS only)
__filename;                    // current file path (CJS only)

// Setting a global variable (avoid this in production!)
global.appName = 'MyApp';
console.log(appName); // accessible anywhere — but pollutes global scope
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 11. What is process object in Node.js?

`process` is a **global object** that provides information and control over the current Node.js process (the running instance of your app).

```js
// Key process properties and methods
process.version;           // Node.js version e.g. 'v20.11.0'
process.platform;          // 'linux', 'win32', 'darwin'
process.pid;               // process ID
process.env;               // environment variables object
process.argv;              // command-line arguments array
process.cwd();             // current working directory
process.exit(0);           // exit process (0 = success, 1 = error)
process.memoryUsage();     // memory usage stats

// process.env example
const PORT = process.env.PORT || 3000;

// process.argv example
// node app.js --port 4000
console.log(process.argv); // ['node', '/path/to/app.js', '--port', '4000']

// Catching uncaught exceptions
process.on('uncaughtException', (err) => {
  console.error('Uncaught exception:', err);
  process.exit(1);
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 12. What is the difference between synchronous and asynchronous code?

| Feature | Synchronous | Asynchronous |
| ------- | ----------- | ------------ |
| Execution | Line by line, blocks until done | Non-blocking — continues execution |
| Thread usage | Blocks the thread | Frees the thread while waiting |
| Use case | Simple scripts, CPU tasks | I/O operations, API calls, DB queries |
| Performance | Poor for I/O |  Excellent for I/O |

```js
const fs = require('fs');

// Synchronous — blocks the thread until file is read
const data = fs.readFileSync('file.txt', 'utf8');
console.log(data);
console.log('This runs AFTER the file is read');

// Asynchronous — non-blocking
fs.readFile('file.txt', 'utf8', (err, data) => {
  if (err) throw err;
  console.log(data);
});
console.log('This runs BEFORE the file is read (non-blocking)');
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 13. What are callbacks in Node.js?

A callback is a **function passed as an argument** to another function, to be called when an asynchronous operation completes.

Node.js uses the **error-first callback** convention (also called Node callback style): the first argument is always an error object (or `null` if no error), followed by the result.

```js
const fs = require('fs');

// Error-first callback pattern
fs.readFile('data.json', 'utf8', (err, data) => {
  if (err) {
    console.error('Error reading file:', err.message);
    return; // always return after error to prevent further execution
  }
  const parsed = JSON.parse(data);
  console.log('Data:', parsed);
});

// Custom function with callback
function fetchUser(id, callback) {
  setTimeout(() => {
    if (id <= 0) {
      callback(new Error('Invalid ID'), null);
    } else {
      callback(null, { id, name: 'Sisi' });
    }
  }, 1000);
}

fetchUser(1, (err, user) => {
  if (err) return console.error(err.message);
  console.log('User:', user);
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 14. What is callback hell? How do you avoid it?

Callback hell (also called the **Pyramid of Doom**) is a situation where multiple nested callbacks make code deeply indented, hard to read, and hard to maintain.

```js
//   Callback hell — deeply nested
getUser(userId, (err, user) => {
  if (err) return handleError(err);
  getOrders(user.id, (err, orders) => {
    if (err) return handleError(err);
    getProducts(orders[0].id, (err, products) => {
      if (err) return handleError(err);
        getReviews(products[0].id, (err, reviews) => {
          if (err) return handleError(err);
          console.log(reviews); // 4 levels deep!
        });
    });
  });
});

//  Solution 1: Promises
getUser(userId)
  .then(user => getOrders(user.id))
  .then(orders => getProducts(orders[0].id))
  .then(products => getReviews(products[0].id))
  .then(reviews => console.log(reviews))
  .catch(handleError);

//  Solution 2: async/await (cleanest)
async function getData(userId) {
  try {
    const user = await getUser(userId);
    const orders = await getOrders(user.id);
    const products = await getProducts(orders[0].id);
    const reviews = await getReviews(products[0].id);
    console.log(reviews);
  } catch (err) {
    handleError(err);
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 15. What are Promises in Node.js?

A Promise is an object representing the **eventual completion or failure** of an asynchronous operation. It has three states: `pending`, `fulfilled`, and `rejected`.

```js
// Creating a Promise
function fetchData(id) {
  return new Promise((resolve, reject) => {
    setTimeout(() => {
      if (id > 0) {
        resolve({ id, data: 'Success!' }); // fulfilled
      } else {
        reject(new Error('Invalid ID'));   // rejected
      }
    }, 1000);
  });
}

// Consuming a Promise
fetchData(1)
  .then(result => console.log(result))    // { id: 1, data: 'Success!' }
  .catch(err => console.error(err.message))
  .finally(() => console.log('Done'));    // always runs

// Promise combinators
Promise.all([fetchData(1), fetchData(2)])       // waits for ALL — fails if any fails
  .then(([r1, r2]) => console.log(r1, r2));

Promise.allSettled([fetchData(1), fetchData(-1)]) // waits for ALL — never fails
  .then(results => console.log(results));

Promise.race([fetchData(1), fetchData(2)])       // resolves with the FIRST settled
  .then(fastest => console.log(fastest));

Promise.any([fetchData(-1), fetchData(2)])       // resolves with the FIRST fulfilled
  .then(first => console.log(first));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 16. What is async/await in Node.js?

`async/await` is **syntactic sugar over Promises** that makes asynchronous code look and behave like synchronous code — much more readable.

```js
const axios = require('axios');

// async function always returns a Promise
async function fetchGitHubUser(username) {
  try {
    const response = await axios.get(`https://api.github.com/users/${username}`);
    const { name, public_repos, followers } = response.data;
    return { name, repos: public_repos, followers };
  } catch (error) {
    if (error.response?.status === 404) {
      throw new Error(`User ${username} not found`);
    }
    throw error;
  }
}

// Usage
async function main() {
  const user = await fetchGitHubUser('sisi-tarak');
  console.log(user);
}

main().catch(console.error);

// Parallel execution with async/await
async function getMultipleUsers() {
  //   Sequential — slow (waits one by one)
  const user1 = await fetchGitHubUser('user1');
  const user2 = await fetchGitHubUser('user2');

  //  Parallel — fast (both run simultaneously)
  const [u1, u2] = await Promise.all([
    fetchGitHubUser('user1'),
    fetchGitHubUser('user2')
  ]);
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 17. What is the fs module in Node.js?

The `fs` (File System) module provides an API to interact with the file system — reading, writing, updating, and deleting files and directories.

```js
const fs = require('fs');
const fsPromises = require('fs').promises; // Promise-based API

// Read file (async callback)
fs.readFile('data.txt', 'utf8', (err, data) => {
  if (err) throw err;
  console.log(data);
});

// Read file (Promise-based — preferred)
async function readData() {
  const data = await fsPromises.readFile('data.txt', 'utf8');
  return data;
}

// Write file
await fsPromises.writeFile('output.txt', 'Hello Sisi!', 'utf8');

// Append to file
await fsPromises.appendFile('log.txt', `[${new Date()}] Request received\n`);

// Check if file exists
const exists = await fsPromises.access('file.txt').then(() => true).catch(() => false);

// Delete file
await fsPromises.unlink('temp.txt');

// Create directory
await fsPromises.mkdir('uploads', { recursive: true });

// Read directory
const files = await fsPromises.readdir('./src');
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 18. What is the path module in Node.js?

The `path` module provides utilities for **working with file and directory paths** in a cross-platform way (handles differences between Windows `\` and Unix `/`).

```js
const path = require('path');

path.join('/users', 'sisi', 'documents', 'file.txt');
// → '/users/sisi/documents/file.txt'

path.resolve('src', 'controllers', 'user.js');
// → '/absolute/path/to/src/controllers/user.js'

path.basename('/home/sisi/file.txt');      // 'file.txt'
path.basename('/home/sisi/file.txt', '.txt'); // 'file'
path.dirname('/home/sisi/file.txt');       // '/home/sisi'
path.extname('server.js');                 // '.js'

path.parse('/home/sisi/notes.txt');
// { root: '/', dir: '/home/sisi', base: 'notes.txt', ext: '.txt', name: 'notes' }

// Common pattern — build absolute paths from __dirname
const configPath = path.join(__dirname, 'config', 'db.js');
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 19. What is the os module in Node.js?

The `os` module provides information about the **operating system** the Node.js process is running on.

```js
const os = require('os');

os.platform();        // 'linux', 'win32', 'darwin'
os.arch();            // 'x64', 'arm64'
os.hostname();        // machine's hostname
os.homedir();         // '/home/sisi'
os.tmpdir();          // '/tmp'
os.uptime();          // system uptime in seconds
os.freemem();         // free memory in bytes
os.totalmem();        // total memory in bytes
os.cpus();            // array of CPU core info
os.networkInterfaces(); // network interface details
os.EOL;               // '\n' on Unix, '\r\n' on Windows

// Practical use — show system stats
console.log(`Platform: ${os.platform()}`);
console.log(`Free Memory: ${(os.freemem() / 1024 / 1024).toFixed(2)} MB`);
console.log(`CPUs: ${os.cpus().length} cores`);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 20. What is the http module in Node.js?

The `http` module is a **core module** that allows Node.js to create HTTP servers and make HTTP requests — without any external library.

```js
const http = require('http');

// Creating an HTTP server
const server = http.createServer((req, res) => {
  const { method, url } = req;

  // Route handling
  if (method === 'GET' && url === '/') {
    res.writeHead(200, { 'Content-Type': 'application/json' });
    res.end(JSON.stringify({ message: 'Welcome to Node.js!' }));
  } else if (method === 'GET' && url === '/health') {
    res.writeHead(200);
    res.end('OK');
  } else {
    res.writeHead(404);
    res.end('Not Found');
  }
});

server.listen(3000, () => {
  console.log('Server running at http://localhost:3000');
});

// Making HTTP requests
http.get('http://api.example.com/data', (res) => {
  let data = '';
  res.on('data', chunk => data += chunk);
  res.on('end', () => console.log(JSON.parse(data)));
});
```

> **Note:** In production, use **Express.js** instead of the raw `http` module for easier routing, middleware, and error handling.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 21. What is the difference between __dirname and __filename?

Both are **global variables available in CommonJS modules** (not in ES Modules without workarounds):

| Variable | Returns |
| -------- | ------- |
| `__dirname` | Absolute path of the **directory** containing the current file |
| `__filename` | Absolute path of the **current file** itself |

```js
// If file is at: /home/sisi/project/src/app.js

console.log(__dirname);   // '/home/sisi/project/src'
console.log(__filename);  // '/home/sisi/project/src/app.js'

// Common use — building absolute paths
const configPath = path.join(__dirname, '..', 'config', 'db.json');
// → '/home/sisi/project/config/db.json'

// In ES Modules (no __dirname available — workaround):
import { fileURLToPath } from 'url';
import { dirname } from 'path';
const __filename = fileURLToPath(import.meta.url);
const __dirname = dirname(__filename);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 22. What is REPL in Node.js?

REPL stands for **Read-Eval-Print Loop** — an interactive programming environment built into Node.js that lets you execute JavaScript code line by line.

```bash
# Start REPL by typing 'node' in terminal
$ node

> 2 + 2
4
> const name = 'Sisi'
undefined
> `Hello ${name}`
'Hello Sisi'
> [1, 2, 3].map(n => n * 2)
[ 2, 4, 6 ]
> .help     # show REPL commands
> .exit     # exit REPL
> .clear    # clear context
> .save file.js  # save session to file
> .load file.js  # load file into session
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 23. What is the difference between dependencies and devDependencies?

| Type | Key | Purpose | Included in production? |
| ---- | --- | ------- | ----------------------- |
| `dependencies` | Runtime packages | Needed for the app to run (Express, Mongoose) |  Yes |
| `devDependencies` | Development-only packages | Testing, linting, building (Jest, nodemon, ESLint) |   No |

```bash
# Add to dependencies (production)
npm install express mongoose jsonwebtoken

# Add to devDependencies
npm install jest nodemon eslint --save-dev

# Install only production dependencies (for deployment)
npm install --production
# or
NODE_ENV=production npm install
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 24. What is package-lock.json? Why is it important?

`package-lock.json` is an **auto-generated file** that locks the exact version of every installed package (including transitive dependencies) at the time of installation.

**Why it matters:**
- Ensures **reproducible builds** — same versions installed on every machine and CI/CD server
- Prevents "works on my machine" problems caused by minor version differences
- Records the exact dependency tree with checksums for integrity verification

```bash
# Always commit package-lock.json to version control
git add package-lock.json

# npm install uses package-lock.json to install exact versions
npm install

# npm ci (clean install) — strictly respects package-lock.json
# faster and safer for CI/CD pipelines
npm ci
```

> **Rule:** Always commit `package-lock.json` but never manually edit it.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 25. What are environment variables? How do you use them in Node.js?

Environment variables are **key-value pairs** stored outside your code that configure your application's behaviour — allowing different configs for development, staging, and production without changing code.

```bash
# .env file (never commit to Git!)
PORT=3000
NODE_ENV=development
DB_URI=mongodb://localhost:27017/myapp
JWT_SECRET=super_secret_key_here
AWS_ACCESS_KEY=AKIAIOSFODNN7EXAMPLE
```

```js
// Install dotenv
// npm install dotenv

// Load .env at app entry point (as early as possible)
require('dotenv').config();

// Access env vars via process.env
const PORT = process.env.PORT || 3000;
const DB_URI = process.env.DB_URI;
const isProduction = process.env.NODE_ENV === 'production';

console.log(`Running on port ${PORT} in ${process.env.NODE_ENV} mode`);

// .gitignore — always exclude .env
// .env
// node_modules/
```

> **Best practice:** Never hardcode secrets or API keys in your code. Always use environment variables.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Event Loop & Core Concepts

<br>

### 26. What is the Event Loop in Node.js?

The Event Loop is the **core mechanism** that enables Node.js to perform non-blocking I/O operations despite being single-threaded. It continuously checks if there are any tasks to execute and processes them in order.

**How it works:**
1. Node.js starts and executes the **call stack** (synchronous code)
2. When async operations (I/O, timers) are encountered, they are offloaded to **libuv** (thread pool or OS)
3. When async operations complete, their callbacks are pushed to the appropriate **event queue**
4. The event loop picks up callbacks from queues and pushes them to the call stack when it's empty

```js
console.log('1 - Start');           // sync — runs first

setTimeout(() => {
  console.log('2 - setTimeout');    // macro task queue
}, 0);

Promise.resolve().then(() => {
  console.log('3 - Promise');       // micro task queue
});

process.nextTick(() => {
  console.log('4 - nextTick');      // nextTick queue (highest priority)
});

console.log('5 - End');             // sync — runs second

// Output: 1 → 5 → 4 → 3 → 2
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 27. What are the phases of the Event Loop?

The Event Loop processes tasks in the following phases (in order):

| Phase | What it handles |
| ----- | --------------- |
| **1. timers** | Callbacks from `setTimeout()` and `setInterval()` |
| **2. pending callbacks** | I/O callbacks deferred from the previous loop |
| **3. idle, prepare** | Internal use by Node.js |
| **4. poll** | Retrieves new I/O events and executes their callbacks |
| **5. check** | `setImmediate()` callbacks |
| **6. close callbacks** | `socket.on('close', ...)` callbacks |

**Between each phase**, Node.js processes:
- `process.nextTick()` queue (always processed before moving to next phase)
- **Microtask queue** — `Promise.then()`, `queueMicrotask()`

```
   ┌───────────────────────────┐
┌─>│           timers          │ ← setTimeout, setInterval
│  └─────────────┬─────────────┘
│  ┌─────────────┴─────────────┐
│  │     pending callbacks     │
│  └─────────────┬─────────────┘
│  ┌─────────────┴─────────────┐
│  │       poll (I/O)          │ ← most I/O callbacks run here
│  └─────────────┬─────────────┘
│  ┌─────────────┴─────────────┐
│  │           check           │ ← setImmediate
│  └─────────────┬─────────────┘
└──┤      close callbacks      │
   └───────────────────────────┘
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 28. What is the difference between process.nextTick() and setImmediate()?

| Feature | `process.nextTick()` | `setImmediate()` |
| ------- | --------------------- | ---------------- |
| Queue | nextTick queue | check phase queue |
| Runs | Before next event loop phase | At the check phase (after I/O) |
| Priority | Highest — runs before Promises | Lower |
| Use case | Defer code but before I/O | Defer code to after I/O |

```js
setImmediate(() => console.log('setImmediate'));
process.nextTick(() => console.log('nextTick'));
Promise.resolve().then(() => console.log('Promise'));
console.log('sync');

// Output:
// sync
// nextTick     ← nextTick queue (before microtasks in older Node, same batch in newer)
// Promise      ← microtask queue
// setImmediate ← check phase

// Warning: Recursive process.nextTick() can starve the event loop!
// process.nextTick(function loop() {
//   process.nextTick(loop); //   I/O will never run
// });
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 29. What is libuv in Node.js?

**libuv** is a **multi-platform C library** that provides Node.js with its event loop, asynchronous I/O, and thread pool. It abstracts the differences between operating systems for async operations.

**libuv handles:**
- Event loop implementation
- Async file system operations
- DNS resolution
- TCP/UDP sockets
- Thread pool (for blocking operations)
- Signal handling
- Child processes

```
Node.js App
     ↓
  Node APIs (fs, http, crypto...)
     ↓
   libuv
     ↓
  ┌─────────────────────┐
  │ Event Loop          │
  │ Thread Pool (4-128) │ ← handles blocking I/O (file system, DNS)
  │ OS Async APIs       │ ← handles network I/O (epoll, kqueue, IOCP)
  └─────────────────────┘
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 30. What is the Thread Pool in Node.js?

Despite being single-threaded for JavaScript execution, Node.js uses a **thread pool** (managed by libuv) to handle operations that are inherently blocking at the OS level.

**Default thread pool size:** 4 threads (configurable via `UV_THREADPOOL_SIZE`)

**Operations that use the thread pool:**
- File system operations (`fs.readFile`, `fs.writeFile`)
- DNS lookup (`dns.lookup`)
- Crypto operations (`crypto.pbkdf2`, `crypto.randomBytes`)
- Zlib operations (compression)
- Some user-space native modules

**Operations handled by OS async APIs (no thread pool):**
- TCP/UDP networking
- HTTP/HTTPS requests
- Timers, `setImmediate`

```js
// Increase thread pool size for CPU-intensive apps
process.env.UV_THREADPOOL_SIZE = 8; // set before requiring any module

// Test thread pool usage
const crypto = require('crypto');
const start = Date.now();

// With 4 default threads — 5 tasks queued, 4th waits
for (let i = 0; i < 5; i++) {
  crypto.pbkdf2('password', 'salt', 100000, 64, 'sha512', () => {
    console.log(`Hash ${i} done in ${Date.now() - start}ms`);
  });
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 31. What are Streams in Node.js?

Streams are **objects that let you read data from a source or write data to a destination continuously**, in chunks — rather than loading everything into memory at once. They are the most efficient way to handle large amounts of data (files, network data, etc.).

**Why use streams:**
- Memory efficient — process data chunk by chunk (no full file in RAM)
- Time efficient — start processing data as soon as first chunk arrives
- Composable — pipe multiple streams together

```js
const fs = require('fs');

// Without streams — loads entire 2GB file into memory  
const data = fs.readFileSync('huge-file.csv');
process(data); // might crash with OOM

// With streams — processes chunk by chunk 
const readable = fs.createReadStream('huge-file.csv');
readable.on('data', (chunk) => {
  process(chunk); // chunk is usually 64KB
});
readable.on('end', () => console.log('Done processing'));
readable.on('error', (err) => console.error(err));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 32. What are the types of Streams in Node.js?

| Type | Class | Example |
| ---- | ----- | ------- |
| **Readable** | `stream.Readable` | `fs.createReadStream()`, `http.IncomingMessage` |
| **Writable** | `stream.Writable` | `fs.createWriteStream()`, `http.ServerResponse` |
| **Duplex** | `stream.Duplex` | `net.Socket` (both read and write) |
| **Transform** | `stream.Transform` | `zlib.createGzip()` (reads, transforms, writes) |

```js
const { Transform } = require('stream');

// Custom Transform stream — uppercase text
const upperCase = new Transform({
  transform(chunk, encoding, callback) {
    this.push(chunk.toString().toUpperCase());
    callback();
  }
});

// Use it:
process.stdin.pipe(upperCase).pipe(process.stdout);
// Type "hello" → outputs "HELLO"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 33. What is piping in Node.js streams?

Piping connects a **Readable stream** to a **Writable stream** — automatically flowing data from source to destination and handling backpressure (when the writable is slower than the readable).

```js
const fs = require('fs');
const zlib = require('zlib');

// Example 1: Copy a file using pipe
const readStream = fs.createReadStream('input.txt');
const writeStream = fs.createWriteStream('output.txt');
readStream.pipe(writeStream);

// Example 2: Compress a file (chain multiple pipes)
fs.createReadStream('input.txt')
  .pipe(zlib.createGzip())                    // compress
  .pipe(fs.createWriteStream('input.txt.gz')) // write compressed
  .on('finish', () => console.log('File compressed!'));

// Example 3: Stream HTTP response
const http = require('http');
http.createServer((req, res) => {
  fs.createReadStream('large-video.mp4').pipe(res); // stream file directly to client
}).listen(3000);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 34. What are Buffers in Node.js?

A `Buffer` is a **fixed-size chunk of memory** allocated outside the V8 heap, used to store raw binary data. Buffers are necessary when working with TCP streams, file system operations, or any binary data.

```js
// Creating buffers
const buf1 = Buffer.alloc(10);                   // 10 bytes, filled with zeros
const buf2 = Buffer.from('Hello, Sisi!');         // from string
const buf3 = Buffer.from([72, 101, 108, 108, 111]); // from array

// Reading from buffer
console.log(buf2.toString());         // 'Hello, Sisi!'
console.log(buf2.toString('hex'));    // hex representation
console.log(buf2.toString('base64')); // base64 representation
console.log(buf2.length);            // 12 (bytes)

// Writing to buffer
const buf = Buffer.alloc(20);
buf.write('Node.js');
console.log(buf.toString()); // 'Node.js'

// Comparing buffers
Buffer.from('abc').equals(Buffer.from('abc')); // true
Buffer.compare(buf1, buf2);                    // -1, 0, or 1
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 35. What is the EventEmitter class in Node.js?

`EventEmitter` is a **core class** in Node.js (`events` module) that implements the observer pattern — objects can emit named events and listeners can subscribe to those events.

```js
const EventEmitter = require('events');

// Create an emitter
const emitter = new EventEmitter();

// Register event listeners (subscribe)
emitter.on('userCreated', (user) => {
  console.log(`Welcome email sent to ${user.email}`);
});

emitter.on('userCreated', (user) => {
  console.log(`User ${user.name} added to analytics`);
});

// One-time listener
emitter.once('serverStart', () => {
  console.log('Server started — this runs only once');
});

// Emit events (publish)
emitter.emit('userCreated', { name: 'Sisi', email: 'sisi@example.com' });
emitter.emit('serverStart');
emitter.emit('serverStart'); // ← once listener doesn't run again

// Remove listener
const handler = (data) => console.log(data);
emitter.on('data', handler);
emitter.off('data', handler); // or emitter.removeListener('data', handler)

// Check listener count
emitter.listenerCount('userCreated'); // 2

// Many Node.js core modules extend EventEmitter:
// http.Server, fs.ReadStream, net.Socket, etc.
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 36. What is the difference between EventEmitter and Streams?

| Feature | EventEmitter | Streams |
| ------- | ------------ | ------- |
| Purpose | Custom event publishing/subscribing | Efficient data flow |
| Data | Any event payload | Binary/string data chunks |
| Backpressure |   No |  Yes |
| Built on | Base class | Extends EventEmitter |
| Use case | App-level events (user actions) | File/network data processing |

> Streams are actually built on top of EventEmitter — they emit events like `data`, `end`, `error`, `drain`.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 37. What is clustering in Node.js?

Node.js runs on a **single CPU core** by default. The `cluster` module allows you to create **multiple worker processes** (one per CPU core) that all share the same port — fully utilizing multi-core systems.

```js
const cluster = require('cluster');
const http = require('http');
const os = require('os');

const numCPUs = os.cpus().length;

if (cluster.isMaster) {
  console.log(`Master PID: ${process.pid}`);

  // Fork a worker for each CPU core
  for (let i = 0; i < numCPUs; i++) {
    cluster.fork();
  }

  // Restart crashed workers
  cluster.on('exit', (worker, code, signal) => {
    console.log(`Worker ${worker.process.pid} died. Restarting...`);
    cluster.fork();
  });

} else {
  // Worker processes — each runs an HTTP server on the same port
  http.createServer((req, res) => {
    res.end(`Response from Worker PID: ${process.pid}`);
  }).listen(3000);

  console.log(`Worker PID: ${process.pid} started`);
}
```

> **Production alternative:** Use **PM2** (`pm2 start app.js -i max`) which handles clustering automatically.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 38. What is the Worker Threads module in Node.js?

Worker Threads (introduced in Node.js 10, stable in 12) enable **true parallelism** for CPU-intensive JavaScript tasks by running JS code in separate threads with shared memory support.

```js
const { Worker, isMainThread, parentPort, workerData } = require('worker_threads');

if (isMainThread) {
  // Main thread — spawns a worker
  const worker = new Worker(__filename, {
    workerData: { numbers: [1, 2, 3, 4, 5] }
  });

  worker.on('message', (result) => {
    console.log('Sum from worker:', result); // 15
  });

  worker.on('error', (err) => console.error(err));
  worker.on('exit', (code) => console.log(`Worker exited with code ${code}`));

} else {
  // Worker thread — runs heavy computation
  const { numbers } = workerData;
  const sum = numbers.reduce((a, b) => a + b, 0);
  parentPort.postMessage(sum); // send result back to main thread
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 39. What is the difference between cluster and worker_threads?

| Feature | cluster | worker_threads |
| ------- | ------- | -------------- |
| Runs | Separate Node.js processes | Threads within one process |
| Memory | Separate memory per process | Shared memory via `SharedArrayBuffer` |
| Communication | IPC (Inter-Process Communication) | `postMessage`, `MessageChannel` |
| Crash isolation |  Worker crash doesn't affect master |   Thread crash can affect process |
| Use case | Scale HTTP servers across CPU cores | CPU-intensive computation in one app |
| Overhead | Higher (new process each) | Lower (threads are lighter) |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 40. How does Node.js handle concurrency if it is single-threaded?

Node.js handles concurrency through its **non-blocking I/O model** and **event loop** — not by running multiple threads simultaneously.

**The key insight:** Most work in a web server is **I/O-bound** (waiting for database, file system, network) — not CPU-bound. While waiting for I/O, Node.js can handle thousands of other requests.

```
Request 1: DB query (50ms wait)
Request 2: DB query (50ms wait)
Request 3: DB query (50ms wait)

  Thread-per-request model (Java/PHP style):
Thread 1: ████████████ waits 50ms for DB
Thread 2: ████████████ waits 50ms for DB
Thread 3: ████████████ waits 50ms for DB
(3 threads blocked for 50ms each)

 Node.js event loop model:
Single Thread: Sends all 3 DB queries → does other work → callbacks called on completion
(No thread blocked — event loop is free)
```

> **Rule:** Node.js is NOT good for CPU-intensive tasks (image processing, video encoding, complex math) — those block the single thread. Use Worker Threads or offload to a separate service.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Express.js

<br>

### 41. What is Express.js?

Express.js is a **minimal and flexible Node.js web application framework** that provides a robust set of features for building web and API servers. It is the most popular Node.js framework and is the "E" in the MERN stack.

```js
const express = require('express');
const app = express();

// Middleware
app.use(express.json()); // parse JSON request bodies

// Route
app.get('/', (req, res) => {
  res.json({ message: 'Hello from Express!' });
});

app.listen(3000, () => console.log('Server started on port 3000'));
```

**Why Express over raw http module:**
- Simplified routing
- Middleware support
- Better error handling
- Template engine support
- Huge ecosystem of plugins

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 42. What is middleware in Express.js?

Middleware are **functions that execute during the request-response cycle**. They have access to the `req` (request), `res` (response), and `next` function. Middleware can execute code, modify req/res, end the cycle, or call the next middleware.

```js
const express = require('express');
const app = express();

// Middleware anatomy: (req, res, next) => void
const logger = (req, res, next) => {
  console.log(`[${new Date().toISOString()}] ${req.method} ${req.url}`);
  next(); // ← must call next() to pass control to the next middleware
};

const authMiddleware = (req, res, next) => {
  const token = req.headers.authorization;
  if (!token) {
    return res.status(401).json({ error: 'No token provided' });
  }
  req.user = verifyToken(token); // attach user to request
  next();
};

// Apply middleware globally
app.use(logger);
app.use(express.json());

// Apply to specific route
app.get('/profile', authMiddleware, (req, res) => {
  res.json({ user: req.user });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 43. What are the types of middleware in Express.js?

| Type | Description | Example |
| ---- | ----------- | ------- |
| **Application-level** | Bound to `app` instance, runs for all/some routes | `app.use(logger)` |
| **Router-level** | Bound to a `Router` instance | `router.use(auth)` |
| **Error-handling** | Has 4 parameters `(err, req, res, next)` | Global error handler |
| **Built-in** | Shipped with Express | `express.json()`, `express.static()` |
| **Third-party** | Installed via npm | `cors`, `helmet`, `morgan`, `multer` |

```js
// Third-party middleware
const cors = require('cors');
const helmet = require('helmet');
const morgan = require('morgan');

app.use(helmet());          // security headers
app.use(cors());            // Cross-Origin Resource Sharing
app.use(morgan('dev'));     // HTTP request logging

// Error-handling middleware (4 params — must be LAST)
app.use((err, req, res, next) => {
  console.error(err.stack);
  res.status(err.status || 500).json({ error: err.message });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 44. What is the difference between app.use() and app.get()?

| Feature | `app.use()` | `app.get()` |
| ------- | ----------- | ----------- |
| HTTP methods | All methods (GET, POST, PUT, DELETE...) | Only GET |
| Path matching | Prefix match (`/api` matches `/api/users`) | Exact match (`/api` only) |
| Use case | Middleware, catch-all handlers | Specific GET routes |

```js
// app.use() — matches /api AND /api/users AND /api/anything
app.use('/api', (req, res, next) => {
  console.log('Any request to /api/* hits this');
  next();
});

// app.get() — matches ONLY GET /users (exact path)
app.get('/users', (req, res) => {
  res.json(users);
});

// app.use() without path — matches ALL routes
app.use(express.json()); // applies to every request
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 45. What is the next() function in Express middleware?

`next()` is a **callback function** provided by Express that passes control to the next middleware in the stack. Not calling `next()` leaves the request hanging.

```js
// next() — pass to next middleware
app.use((req, res, next) => {
  req.timestamp = Date.now();
  next(); // continue to next middleware/route
});

// next(err) — pass an error to the error handler
app.use((req, res, next) => {
  if (!req.headers.authorization) {
    next(new Error('Unauthorized')); // skips all regular middleware, goes to error handler
  } else {
    next();
  }
});

// next('route') — skip remaining handlers for current route, go to next route
app.get('/user/:id', (req, res, next) => {
  if (req.params.id === '0') next('route'); // skip to next matching route
  else next();
}, (req, res) => {
  res.json({ id: req.params.id });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 46. How do you handle errors in Express.js?

```js
// 1. Synchronous errors — throw inside route handler
app.get('/sync', (req, res, next) => {
  try {
    const result = riskyOperation();
    res.json(result);
  } catch (err) {
    next(err); // pass to error handling middleware
  }
});

// 2. Async errors — must explicitly call next(err)
app.get('/async', async (req, res, next) => {
  try {
    const data = await fetchFromDB();
    res.json(data);
  } catch (err) {
    next(err);
  }
});

// 3. Custom error class
class AppError extends Error {
  constructor(message, status) {
    super(message);
    this.status = status;
  }
}

app.get('/not-found', (req, res, next) => {
  next(new AppError('Resource not found', 404));
});

// 4. Global error handling middleware (4 params — must be last!)
app.use((err, req, res, next) => {
  console.error(err.stack);
  res.status(err.status || 500).json({
    success: false,
    message: err.message || 'Internal Server Error'
  });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 47. What is the difference between req.params, req.query, and req.body?

| Property | Source | Example URL | Access |
| -------- | ------ | ----------- | ------ |
| `req.params` | URL path parameters (`:id`) | `/users/42` | `req.params.id` → `'42'` |
| `req.query` | URL query string (`?key=val`) | `/users?role=admin&page=2` | `req.query.role` → `'admin'` |
| `req.body` | Request body (POST/PUT/PATCH) | JSON/form body | `req.body.name` → `'Sisi'` |

```js
// Route: /api/users/:userId/posts/:postId?sort=desc&page=1
// With body: { "title": "My Post", "content": "Hello!" }

app.put('/api/users/:userId/posts/:postId', (req, res) => {
  console.log(req.params); // { userId: '5', postId: '12' }
  console.log(req.query);  // { sort: 'desc', page: '1' }
  console.log(req.body);   // { title: 'My Post', content: 'Hello!' }

  res.json({ params: req.params, query: req.query, body: req.body });
});

// Note: req.body requires express.json() middleware
app.use(express.json());
app.use(express.urlencoded({ extended: true })); // for form submissions
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 48. What is Express Router?

Express Router is a **mini-application** that can handle routing and middleware — used to organize routes into separate files/modules for cleaner architecture.

```js
// routes/userRoutes.js
const express = require('express');
const router = express.Router();
const { authMiddleware } = require('../middleware/auth');
const userController = require('../controllers/userController');

router.use(authMiddleware); // applies to all routes in this router

router.get('/', userController.getAllUsers);
router.get('/:id', userController.getUserById);
router.post('/', userController.createUser);
router.put('/:id', userController.updateUser);
router.delete('/:id', userController.deleteUser);

module.exports = router;

// app.js — mount the router
const userRoutes = require('./routes/userRoutes');
app.use('/api/users', userRoutes);
// → GET /api/users, GET /api/users/:id, POST /api/users, etc.
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 49. How do you serve static files in Express.js?

```js
const express = require('express');
const path = require('path');
const app = express();

// Serve static files from 'public' directory
app.use(express.static(path.join(__dirname, 'public')));
// → /public/index.html accessible at http://localhost:3000/index.html
// → /public/images/logo.png accessible at http://localhost:3000/images/logo.png

// Serve with a virtual path prefix
app.use('/static', express.static(path.join(__dirname, 'public')));
// → /public/style.css accessible at http://localhost:3000/static/style.css

// Serve React build files (SPA deployment)
app.use(express.static(path.join(__dirname, 'client/build')));
app.get('*', (req, res) => {
  res.sendFile(path.join(__dirname, 'client/build', 'index.html'));
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 50. What is CORS? How do you handle it in Node.js?

**CORS (Cross-Origin Resource Sharing)** is a browser security mechanism that **blocks HTTP requests** made from a different origin (domain, protocol, or port) than the server by default.

```js
// Without CORS — browser blocks requests from http://localhost:3000 to http://localhost:5000

//  Using the cors package (recommended)
const cors = require('cors');

// Allow all origins (development only — dangerous in production!)
app.use(cors());

// Production — configure specific origins
app.use(cors({
  origin: ['https://myapp.com', 'https://www.myapp.com'],
  methods: ['GET', 'POST', 'PUT', 'DELETE'],
  allowedHeaders: ['Content-Type', 'Authorization'],
  credentials: true // allow cookies
}));

// Per-route CORS
app.get('/public-data', cors(), (req, res) => {
  res.json({ data: 'This is public' });
});

// Manual CORS headers (without package)
app.use((req, res, next) => {
  res.setHeader('Access-Control-Allow-Origin', 'https://myapp.com');
  res.setHeader('Access-Control-Allow-Methods', 'GET, POST, PUT, DELETE');
  res.setHeader('Access-Control-Allow-Headers', 'Content-Type, Authorization');
  if (req.method === 'OPTIONS') return res.sendStatus(204); // preflight
  next();
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Database & APIs

<br>

### 51. How do you connect Node.js to MongoDB?

```js
const mongoose = require('mongoose');

// Connection with best practices
async function connectDB() {
  try {
    await mongoose.connect(process.env.MONGO_URI, {
      useNewUrlParser: true,
      useUnifiedTopology: true
    });
    console.log('MongoDB connected successfully');
  } catch (err) {
    console.error('MongoDB connection failed:', err.message);
    process.exit(1); // exit if DB connection fails
  }
}

connectDB();

// Connection events
mongoose.connection.on('disconnected', () => console.log('MongoDB disconnected'));
mongoose.connection.on('error', (err) => console.error('DB error:', err));

// Graceful shutdown
process.on('SIGINT', async () => {
  await mongoose.connection.close();
  process.exit(0);
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 52. What is Mongoose? What are its advantages?

Mongoose is an **ODM (Object Data Modelling) library** for MongoDB and Node.js. It provides schema-based modelling, validation, middleware hooks, and a rich query API.

```js
const mongoose = require('mongoose');

// Define schema
const userSchema = new mongoose.Schema({
  name: { type: String, required: [true, 'Name is required'], trim: true },
  email: { type: String, required: true, unique: true, lowercase: true },
  age: { type: Number, min: 0, max: 120 },
  role: { type: String, enum: ['user', 'admin', 'editor'], default: 'user' },
  createdAt: { type: Date, default: Date.now }
});

// Virtual (computed property — not saved to DB)
userSchema.virtual('displayName').get(function() {
  return `${this.name} (${this.role})`;
});

// Pre-save hook (middleware)
userSchema.pre('save', async function(next) {
  if (this.isModified('password')) {
    this.password = await bcrypt.hash(this.password, 12);
  }
  next();
});

// Instance method
userSchema.methods.toSafeObject = function() {
  return { id: this._id, name: this.name, email: this.email };
};

// Static method
userSchema.statics.findByEmail = function(email) {
  return this.findOne({ email });
};

const User = mongoose.model('User', userSchema);

// CRUD operations
const user = await User.create({ name: 'Sisi', email: 'sisi@example.com' });
const users = await User.find({ role: 'admin' }).select('name email').limit(10);
const updated = await User.findByIdAndUpdate(id, { name: 'Sisi 2.0' }, { new: true });
await User.findByIdAndDelete(id);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 53. What is the difference between SQL and NoSQL databases?

| Feature | SQL (Relational) | NoSQL |
| ------- | ---------------- | ----- |
| Structure | Tables with rows and columns | Documents, key-value, graphs, columns |
| Schema | Fixed, predefined | Flexible/dynamic |
| Scaling | Vertical (scale up) | Horizontal (scale out) |
| ACID compliance |  Strong | Varies (MongoDB is ACID in v4+) |
| Joins |  Native joins | Manual/embedded documents |
| Best for | Structured data, complex queries | Unstructured/large-scale, flexible data |
| Examples | MySQL, PostgreSQL, SQLite | MongoDB, Redis, Cassandra, DynamoDB |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 54. How do you connect Node.js to a SQL database?

```js
// Using pg (PostgreSQL)
const { Pool } = require('pg');

const pool = new Pool({
  host: process.env.DB_HOST,
  port: 5432,
  database: process.env.DB_NAME,
  user: process.env.DB_USER,
  password: process.env.DB_PASSWORD,
  max: 20,        // max connections in pool
  idleTimeoutMillis: 30000
});

// Query with parameterized values (prevents SQL injection)
const getUser = async (userId) => {
  const { rows } = await pool.query(
    'SELECT id, name, email FROM users WHERE id = $1',
    [userId]
  );
  return rows[0];
};

// Using mysql2
const mysql = require('mysql2/promise');
const connection = await mysql.createConnection({
  host: 'localhost',
  user: 'root',
  database: 'myapp'
});
const [rows] = await connection.execute('SELECT * FROM users WHERE id = ?', [1]);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 55. What is an ORM? Name popular ORMs for Node.js

An **ORM (Object-Relational Mapper)** maps database tables to JavaScript classes/objects — allowing you to query and manipulate data using code instead of raw SQL.

| ORM/ODM | Database | Notable features |
| ------- | -------- | --------------- |
| **Mongoose** | MongoDB | Schema validation, middleware, virtuals |
| **Prisma** | PostgreSQL, MySQL, SQLite, MongoDB | Type-safe, auto-generated client, migrations |
| **Sequelize** | MySQL, PostgreSQL, SQLite, MSSQL | Full-featured, associations, migrations |
| **TypeORM** | All SQL + MongoDB | TypeScript-first, decorators |
| **Drizzle** | PostgreSQL, MySQL, SQLite | Lightweight, SQL-like syntax |
| **Knex.js** | SQL (query builder, not full ORM) | Raw SQL control + builder API |

```js
// Prisma example — type-safe queries
const user = await prisma.user.create({
  data: { name: 'Sisi', email: 'sisi@example.com' }
});

const users = await prisma.user.findMany({
  where: { role: 'ADMIN' },
  include: { posts: true }, // join
  orderBy: { createdAt: 'desc' }
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 56. What is REST API? How do you build one in Node.js?

REST (Representational State Transfer) is an **architectural style** for building APIs using standard HTTP methods and stateless communication.

```js
const express = require('express');
const router = express.Router();

// GET    /api/products     → get all products
// GET    /api/products/:id → get single product
// POST   /api/products     → create product
// PUT    /api/products/:id → update full product
// PATCH  /api/products/:id → update partial product
// DELETE /api/products/:id → delete product

router.get('/', async (req, res, next) => {
  try {
    const { page = 1, limit = 10 } = req.query;
    const products = await Product.find()
      .skip((page - 1) * limit).limit(Number(limit));
    res.json({ success: true, data: products });
  } catch (err) { next(err); }
});

router.post('/', async (req, res, next) => {
  try {
    const product = await Product.create(req.body);
    res.status(201).json({ success: true, data: product });
  } catch (err) { next(err); }
});

router.put('/:id', async (req, res, next) => {
  try {
    const product = await Product.findByIdAndUpdate(req.params.id, req.body, { new: true, runValidators: true });
    if (!product) return res.status(404).json({ error: 'Product not found' });
    res.json({ success: true, data: product });
  } catch (err) { next(err); }
});

router.delete('/:id', async (req, res, next) => {
  try {
    await Product.findByIdAndDelete(req.params.id);
    res.status(204).send(); // 204 No Content
  } catch (err) { next(err); }
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 57. What are HTTP methods and their purposes?

| Method | Purpose | Idempotent? | Has Body? |
| ------ | ------- | ----------- | --------- |
| `GET` | Retrieve a resource |  Yes |   No |
| `POST` | Create a new resource |   No |  Yes |
| `PUT` | Replace a resource entirely |  Yes |  Yes |
| `PATCH` | Partially update a resource |  Yes |  Yes |
| `DELETE` | Delete a resource |  Yes | Optional |
| `HEAD` | Same as GET but no response body |  Yes |   No |
| `OPTIONS` | Get allowed methods for a resource (preflight) |  Yes |   No |

> **Idempotent** means: calling the same request multiple times produces the same result as calling it once.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 58. What are HTTP status codes? List important ones

| Code | Name | Meaning |
| ---- | ---- | ------- |
| **200** | OK | Request successful |
| **201** | Created | Resource created successfully |
| **204** | No Content | Success, no body (DELETE) |
| **301** | Moved Permanently | Resource permanently moved |
| **304** | Not Modified | Cached version is still valid |
| **400** | Bad Request | Invalid input/request |
| **401** | Unauthorized | Not authenticated |
| **403** | Forbidden | Authenticated but not authorized |
| **404** | Not Found | Resource doesn't exist |
| **409** | Conflict | Duplicate resource (e.g., email exists) |
| **422** | Unprocessable Entity | Validation failed |
| **429** | Too Many Requests | Rate limit exceeded |
| **500** | Internal Server Error | Generic server error |
| **502** | Bad Gateway | Upstream server error |
| **503** | Service Unavailable | Server down/overloaded |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 59. What is GraphQL? How is it different from REST?

| Feature | REST | GraphQL |
| ------- | ---- | ------- |
| Endpoints | Multiple (`/users`, `/posts`, `/comments`) | Single endpoint (`/graphql`) |
| Data fetching | Fixed response structure | Client specifies exact fields needed |
| Over-fetching | Common |   Eliminated |
| Under-fetching | Requires multiple requests |   Single request gets all related data |
| Versioning | Required (`/api/v1/`, `/api/v2/`) | Not needed (add fields without breaking) |
| Learning curve | Low | Higher |
| Best for | Simple CRUD APIs | Complex, nested data; multiple clients |

```js
// REST — multiple requests to get user + their posts + their followers
GET /api/users/1
GET /api/users/1/posts
GET /api/users/1/followers

// GraphQL — one request, exactly the fields you need
query {
  user(id: "1") {
    name
    email
    posts(limit: 5) { title createdAt }
    followers { name }
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 60. What is pagination? How do you implement it in Node.js?

Pagination divides large datasets into smaller pages to avoid returning thousands of records at once, improving performance and UX.

```js
// Offset/Limit pagination (simple)
app.get('/api/products', async (req, res) => {
  const page = parseInt(req.query.page) || 1;
  const limit = parseInt(req.query.limit) || 10;
  const skip = (page - 1) * limit;

  const [products, total] = await Promise.all([
    Product.find().skip(skip).limit(limit).sort({ createdAt: -1 }),
    Product.countDocuments()
  ]);

  res.json({
    data: products,
    pagination: {
      page,
      limit,
      total,
      totalPages: Math.ceil(total / limit),
      hasNextPage: page < Math.ceil(total / limit),
      hasPrevPage: page > 1
    }
  });
});

// Cursor-based pagination (efficient for large datasets)
app.get('/api/feed', async (req, res) => {
  const limit = 10;
  const cursor = req.query.cursor; // last item's ID

  const query = cursor ? { _id: { $lt: cursor } } : {};
  const items = await Post.find(query).sort({ _id: -1 }).limit(limit + 1);

  const hasMore = items.length > limit;
  const data = hasMore ? items.slice(0, -1) : items;

  res.json({ data, nextCursor: hasMore ? data[data.length - 1]._id : null });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Authentication & Security

<br>

### 61. What is JWT? How does it work?

**JWT (JSON Web Token)** is an open standard for securely transmitting information between parties as a digitally signed JSON object. It is the most common method for **stateless authentication** in Node.js APIs.

**JWT structure:** `header.payload.signature` (Base64 encoded)

```
eyJhbGciOiJIUzI1NiJ9  ← Header (algorithm & type)
.eyJzdWIiOiIxMjM0In0  ← Payload (claims: userId, role, exp)
.SflKxwRJSMeKKF2QT4f  ← Signature (HMAC with secret key)
```

**How JWT authentication works:**
1. User logs in with credentials
2. Server verifies credentials → generates JWT with `userId`, `role`, expiry
3. Server sends JWT to client
4. Client stores JWT (memory / httpOnly cookie)
5. Client sends JWT in `Authorization: Bearer <token>` header on every request
6. Server verifies JWT signature → extracts user info → processes request

```js
const jwt = require('jsonwebtoken');

// Generate token (on login)
const token = jwt.sign(
  { userId: user._id, role: user.role }, // payload
  process.env.JWT_SECRET,                 // secret key
  { expiresIn: '7d' }                    // expiry
);

// Verify token (middleware)
const verifyToken = (req, res, next) => {
  const token = req.headers.authorization?.split(' ')[1]; // 'Bearer <token>'
  if (!token) return res.status(401).json({ error: 'No token' });

  try {
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = decoded;
    next();
  } catch (err) {
    res.status(401).json({ error: 'Invalid or expired token' });
  }
};
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 62. What is the difference between authentication and authorization?

| Concept | Authentication | Authorization |
| ------- | -------------- | ------------- |
| Question | "Who are you?" | "What can you do?" |
| Checks | Identity (username/password, token) | Permissions (role, ownership) |
| Status code | 401 Unauthorized | 403 Forbidden |
| Example | Login with email + password | Admin can delete; user cannot |

```js
// Authentication middleware — verifies identity
const authenticate = (req, res, next) => {
  const token = req.headers.authorization?.split(' ')[1];
  if (!token) return res.status(401).json({ error: 'Please log in' });
  req.user = jwt.verify(token, process.env.JWT_SECRET);
  next();
};

// Authorization middleware — checks permissions
const authorize = (...roles) => (req, res, next) => {
  if (!roles.includes(req.user.role)) {
    return res.status(403).json({ error: 'You do not have permission' });
  }
  next();
};

// Usage
router.delete('/users/:id',
  authenticate,              // must be logged in
  authorize('admin'),        // must be admin
  userController.deleteUser
);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 63. How do you implement JWT authentication in Node.js?

```js
// Full JWT auth implementation
const express = require('express');
const jwt = require('jsonwebtoken');
const bcrypt = require('bcryptjs');
const User = require('./models/User');

const router = express.Router();

// Register
router.post('/register', async (req, res, next) => {
  try {
    const { name, email, password } = req.body;
    const hashedPassword = await bcrypt.hash(password, 12);
    const user = await User.create({ name, email, password: hashedPassword });
    res.status(201).json({ message: 'User registered successfully' });
  } catch (err) { next(err); }
});

// Login
router.post('/login', async (req, res, next) => {
  try {
    const { email, password } = req.body;
    const user = await User.findOne({ email });
    if (!user || !(await bcrypt.compare(password, user.password))) {
      return res.status(401).json({ error: 'Invalid credentials' });
    }

    const accessToken = jwt.sign(
      { userId: user._id, role: user.role },
      process.env.JWT_SECRET,
      { expiresIn: '15m' }  // short-lived
    );
    const refreshToken = jwt.sign(
      { userId: user._id },
      process.env.JWT_REFRESH_SECRET,
      { expiresIn: '7d' }   // long-lived
    );

    // Send refresh token as httpOnly cookie (more secure)
    res.cookie('refreshToken', refreshToken, { httpOnly: true, secure: true, sameSite: 'Strict' });
    res.json({ accessToken });
  } catch (err) { next(err); }
});

// Refresh token
router.post('/refresh', (req, res) => {
  const { refreshToken } = req.cookies;
  if (!refreshToken) return res.status(401).json({ error: 'No refresh token' });
  const decoded = jwt.verify(refreshToken, process.env.JWT_REFRESH_SECRET);
  const newAccessToken = jwt.sign({ userId: decoded.userId }, process.env.JWT_SECRET, { expiresIn: '15m' });
  res.json({ accessToken: newAccessToken });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 64. What is bcrypt? Why do you hash passwords?

**bcrypt** is a password hashing library that uses a **slow, adaptive hashing algorithm** — making brute-force attacks computationally infeasible even if the database is compromised.

**Why hash passwords:**
- Never store plain-text passwords — if DB is hacked, all accounts are compromised
- bcrypt is deliberately slow (configurable work factor) — 10,000 attempts/sec vs billions for MD5
- Each hash includes a unique **salt** — prevents rainbow table attacks

```js
const bcrypt = require('bcryptjs');

// Hashing (during registration)
const saltRounds = 12; // work factor — higher = slower but more secure
const hashedPassword = await bcrypt.hash('myPassword123', saltRounds);
// → '$2a$12$someRandomSaltHere.hashedPasswordHere'

// Verifying (during login)
const isMatch = await bcrypt.compare('myPassword123', hashedPassword); // true
const isMatch2 = await bcrypt.compare('wrongPassword', hashedPassword); // false

//   Never do this:
user.password = 'plaintext'; // exposed if DB is compromised

//  Always do this:
user.password = await bcrypt.hash(plainTextPassword, 12);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 65. What is OAuth 2.0?

OAuth 2.0 is an **authorization framework** that allows third-party applications to access a user's resources (on another service) **without exposing their password** — using access tokens.

**Common OAuth 2.0 flows:**

| Flow | Use case |
| ---- | -------- |
| Authorization Code | Web apps (most secure — backend handles tokens) |
| PKCE | Single-page apps and mobile apps |
| Client Credentials | Server-to-server (no user involved) |
| Implicit | Deprecated — not recommended |

```js
// OAuth 2.0 with Google using Passport.js
const passport = require('passport');
const GoogleStrategy = require('passport-google-oauth20').Strategy;

passport.use(new GoogleStrategy({
  clientID: process.env.GOOGLE_CLIENT_ID,
  clientSecret: process.env.GOOGLE_CLIENT_SECRET,
  callbackURL: '/auth/google/callback'
},
async (accessToken, refreshToken, profile, done) => {
  // Find or create user in DB
  let user = await User.findOne({ googleId: profile.id });
  if (!user) {
    user = await User.create({
      googleId: profile.id,
      name: profile.displayName,
      email: profile.emails[0].value
    });
  }
  done(null, user);
}));

app.get('/auth/google', passport.authenticate('google', { scope: ['profile', 'email'] }));
app.get('/auth/google/callback', passport.authenticate('google', { session: false }),
  (req, res) => {
    const token = jwt.sign({ userId: req.user._id }, process.env.JWT_SECRET, { expiresIn: '7d' });
    res.redirect(`https://myapp.com?token=${token}`);
  }
);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 66. What is helmet.js? What security headers does it set?

**helmet** is a middleware that sets various **HTTP security headers** to protect your Express app from common web vulnerabilities.

```js
const helmet = require('helmet');
app.use(helmet()); // enables all defaults at once

// Headers helmet sets:
// Content-Security-Policy   — prevents XSS by specifying allowed content sources
// X-DNS-Prefetch-Control    — controls browser DNS prefetching
// X-Frame-Options           — prevents clickjacking (DENY / SAMEORIGIN)
// X-Powered-By              — removes "X-Powered-By: Express" header
// Strict-Transport-Security — forces HTTPS (HSTS)
// X-Content-Type-Options    — prevents MIME sniffing
// X-XSS-Protection          — legacy XSS filter for older browsers
// Referrer-Policy           — controls referrer header

// Custom configuration
app.use(helmet({
  contentSecurityPolicy: {
    directives: {
      defaultSrc: ["'self'"],
      scriptSrc: ["'self'", "trusted-cdn.com"],
      imgSrc: ["'self'", "data:", "*.cloudinary.com"]
    }
  },
  hsts: { maxAge: 31536000, includeSubDomains: true }
}));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 67. What is rate limiting? How do you implement it?

Rate limiting **restricts the number of requests** a client can make in a given time window — protecting against brute-force attacks, DDoS, and API abuse.

```js
const rateLimit = require('express-rate-limit');

// General rate limiter
const limiter = rateLimit({
  windowMs: 15 * 60 * 1000, // 15 minute window
  max: 100,                  // max 100 requests per window
  message: { error: 'Too many requests. Try again in 15 minutes.' },
  standardHeaders: true,     // return rate limit info in headers
  legacyHeaders: false
});

app.use('/api/', limiter);

// Stricter limit for auth endpoints (prevent brute force)
const authLimiter = rateLimit({
  windowMs: 15 * 60 * 1000,
  max: 5, // only 5 login attempts per 15 minutes
  message: { error: 'Too many login attempts. Please try again later.' }
});

app.use('/api/auth/login', authLimiter);
app.use('/api/auth/register', authLimiter);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 68. What is SQL Injection? How do you prevent it in Node.js?

SQL Injection is an attack where **malicious SQL code** is inserted into a query through user input — potentially deleting data, bypassing authentication, or exposing sensitive information.

```js
//   VULNERABLE — raw string interpolation
const userId = req.params.id; // attacker inputs: "1 OR 1=1"
const query = `SELECT * FROM users WHERE id = ${userId}`;
// Executed: SELECT * FROM users WHERE id = 1 OR 1=1 — returns ALL users!

// Another attack: id = "1; DROP TABLE users;"

//  SAFE — parameterized queries (never mix user input into SQL strings)
const { rows } = await pool.query('SELECT * FROM users WHERE id = $1', [userId]);
// pg parameterizes automatically — input is treated as data, not code

//  SAFE — using Prisma (ORM handles parameterization)
const user = await prisma.user.findUnique({ where: { id: userId } });

//  SAFE — using Knex.js
const user = await knex('users').where({ id: userId }).first();

//  Input validation (additional layer — not a replacement)
const { id } = req.params;
if (!mongoose.isValidObjectId(id)) return res.status(400).json({ error: 'Invalid ID' });
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 69. What is CSRF? How do you prevent it?

**CSRF (Cross-Site Request Forgery)** is an attack that tricks an authenticated user into unknowingly submitting a malicious request to a server where they are logged in.

```
Victim logged into bank.com
      ↓
Attacker's site loads: <img src="bank.com/transfer?to=hacker&amount=10000">
      ↓
Browser automatically sends bank.com cookies with request!
```

**Prevention strategies:**

```js
// 1. Use SameSite cookie attribute (best defense)
res.cookie('sessionId', token, {
  httpOnly: true,
  secure: true,
  sameSite: 'Strict' // or 'Lax' — prevents cross-site cookie sending
});

// 2. CSRF tokens (for form submissions)
const csrf = require('csurf');
app.use(csrf({ cookie: true }));
app.get('/form', (req, res) => {
  res.render('form', { csrfToken: req.csrfToken() });
});

// 3. Check Origin/Referer header (additional validation)
app.use((req, res, next) => {
  const origin = req.headers.origin || req.headers.referer;
  if (origin && !origin.startsWith('https://myapp.com')) {
    return res.status(403).json({ error: 'CSRF check failed' });
  }
  next();
});

// 4. JWT in Authorization header (naturally CSRF-safe — browsers don't auto-send)
// Unlike cookies, JS must explicitly attach the header — attackers can't trigger this
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Performance & Architecture

<br>

### 70. What is caching? How do you implement it with Redis in Node.js?

Caching stores **frequently accessed data in fast memory** to avoid expensive repeated database queries or computations.

```js
const redis = require('ioredis');
const client = new redis(process.env.REDIS_URL);

// Cache middleware for Express routes
const cacheMiddleware = (ttl = 3600) => async (req, res, next) => {
  const key = `cache:${req.originalUrl}`;

  try {
    const cached = await client.get(key);
    if (cached) {
      return res.json({ data: JSON.parse(cached), source: 'cache' });
    }
    // Override res.json to intercept and cache the response
    const originalJson = res.json.bind(res);
    res.json = (data) => {
      client.setex(key, ttl, JSON.stringify(data)); // cache for `ttl` seconds
      return originalJson(data);
    };
    next();
  } catch (err) {
    next(); // on cache error, proceed without cache
  }
};

// Usage
app.get('/api/products', cacheMiddleware(300), productController.getAll);

// Cache invalidation — clear when data changes
const invalidateCache = async (pattern) => {
  const keys = await client.keys(pattern); // e.g., 'cache:/api/products*'
  if (keys.length) await client.del(keys);
};

app.post('/api/products', async (req, res, next) => {
  const product = await Product.create(req.body);
  await invalidateCache('cache:/api/products*'); // invalidate product cache
  res.status(201).json({ data: product });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 71. What is a message queue? Name popular ones used with Node.js

A **message queue** is a component that allows services to communicate asynchronously — the sender puts a message in the queue and the receiver processes it independently. This decouples services and enables reliable async processing.

**Use cases:** sending emails, processing payments, image resizing, notifications

| Queue | Protocol | Best for |
| ----- | -------- | -------- |
| **Redis** (Bull/BullMQ) | Redis | Simple queues, job processing |
| **RabbitMQ** | AMQP | Complex routing, message acknowledgement |
| **Apache Kafka** | Custom | High-throughput event streaming |
| **AWS SQS** | HTTP | Cloud-native, managed queue |

```js
// BullMQ with Redis
const { Queue, Worker } = require('bullmq');

// Producer — add jobs to queue
const emailQueue = new Queue('emails', { connection: { host: 'localhost', port: 6379 } });

await emailQueue.add('sendWelcome', { to: 'sisi@example.com', name: 'Sisi' });

// Consumer — process jobs
const worker = new Worker('emails', async (job) => {
  if (job.name === 'sendWelcome') {
    await sendEmail(job.data.to, 'Welcome!', `Hello ${job.data.name}`);
  }
}, { connection: { host: 'localhost', port: 6379 } });

worker.on('completed', (job) => console.log(`Email sent: ${job.id}`));
worker.on('failed', (job, err) => console.error(`Failed: ${job.id}`, err));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 72. What is WebSocket? How do you implement real-time communication in Node.js?

WebSocket is a **bidirectional, persistent communication protocol** that keeps an open connection between client and server — enabling real-time data push without polling.

```js
const WebSocket = require('ws');
const wss = new WebSocket.Server({ port: 8080 });

// Track connected clients
const clients = new Set();

wss.on('connection', (ws, req) => {
  clients.add(ws);
  console.log(`Client connected. Total: ${clients.size}`);

  // Receive message from client
  ws.on('message', (message) => {
    const data = JSON.parse(message);
    // Broadcast to all connected clients
    clients.forEach(client => {
      if (client.readyState === WebSocket.OPEN) {
        client.send(JSON.stringify({ type: 'message', data }));
      }
    });
  });

  // Client disconnected
  ws.on('close', () => {
    clients.delete(ws);
    console.log(`Client disconnected. Total: ${clients.size}`);
  });

  // Send welcome message
  ws.send(JSON.stringify({ type: 'welcome', message: 'Connected to WebSocket!' }));
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 73. What is Socket.IO?

Socket.IO is a library built on top of WebSocket (with fallback to HTTP long-polling) that adds **rooms, namespaces, auto-reconnection, and event broadcasting** — making real-time apps much easier to build.

```js
// Server
const { Server } = require('socket.io');
const io = new Server(httpServer, { cors: { origin: '*' } });

io.on('connection', (socket) => {
  console.log(`User connected: ${socket.id}`);

  // Join a room
  socket.on('joinRoom', (roomId) => {
    socket.join(roomId);
    socket.to(roomId).emit('userJoined', socket.id);
  });

  // Chat message
  socket.on('sendMessage', ({ roomId, message }) => {
    io.to(roomId).emit('newMessage', { from: socket.id, message }); // broadcast to room
  });

  socket.on('disconnect', () => console.log('User disconnected:', socket.id));
});

// Client (browser)
const socket = io('http://localhost:3000');
socket.emit('joinRoom', 'room-123');
socket.on('newMessage', (msg) => console.log(msg));
socket.emit('sendMessage', { roomId: 'room-123', message: 'Hello!' });
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 74. What is the difference between WebSocket and HTTP?

| Feature | HTTP | WebSocket |
| ------- | ---- | --------- |
| Connection | New connection per request | Persistent, single connection |
| Direction | Client → Server (request-response) | Bidirectional (client ↔ server) |
| Overhead | High (headers on every request) | Low (small frames after handshake) |
| Real-time |   Requires polling |  Server can push any time |
| Protocol | `http://` / `https://` | `ws://` / `wss://` |
| Use case | REST APIs, page loads | Chat, live sports, stock tickers, gaming |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 75. How do you handle file uploads in Node.js?

```js
const multer = require('multer');
const path = require('path');

// Configure storage
const storage = multer.diskStorage({
  destination: (req, file, cb) => {
    cb(null, 'uploads/'); // save to uploads/ folder
  },
  filename: (req, file, cb) => {
    const uniqueName = `${Date.now()}-${Math.round(Math.random() * 1E9)}${path.extname(file.originalname)}`;
    cb(null, uniqueName);
  }
});

// File filter — only allow images
const fileFilter = (req, file, cb) => {
  const allowedTypes = /jpeg|jpg|png|gif|webp/;
  const isValid = allowedTypes.test(path.extname(file.originalname).toLowerCase())
    && allowedTypes.test(file.mimetype);
  cb(isValid ? null : new Error('Only image files are allowed!'), isValid);
};

const upload = multer({
  storage,
  fileFilter,
  limits: { fileSize: 5 * 1024 * 1024 } // 5MB limit
});

// Single file upload
app.post('/upload/avatar', upload.single('avatar'), (req, res) => {
  if (!req.file) return res.status(400).json({ error: 'No file uploaded' });
  res.json({ filename: req.file.filename, path: `/uploads/${req.file.filename}` });
});

// Multiple file upload
app.post('/upload/gallery', upload.array('images', 10), (req, res) => {
  const filePaths = req.files.map(f => `/uploads/${f.filename}`);
  res.json({ uploaded: filePaths });
});

// Upload to cloud (Cloudinary) — production approach
const cloudinary = require('cloudinary').v2;
const { CloudinaryStorage } = require('multer-storage-cloudinary');
const cloudStorage = new CloudinaryStorage({ cloudinary, params: { folder: 'my-app' } });
const cloudUpload = multer({ storage: cloudStorage });
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 76. What is PM2? Why is it used in production?

**PM2 (Process Manager 2)** is a production process manager for Node.js that keeps your app **running 24/7**, handles crashes, clustering, logging, and monitoring.

```bash
# Install
npm install -g pm2

# Start app
pm2 start app.js --name "my-api"

# Cluster mode — one instance per CPU core
pm2 start app.js -i max --name "my-api"

# Essential commands
pm2 status           # view all running processes
pm2 logs my-api      # view app logs
pm2 restart my-api   # restart app
pm2 stop my-api      # stop app
pm2 delete my-api    # remove from PM2
pm2 monit            # real-time monitoring dashboard

# Auto-start on system boot
pm2 startup
pm2 save             # save current process list

# Zero-downtime reload (no dropped requests)
pm2 reload my-api
```

```js
// ecosystem.config.js — PM2 config file
module.exports = {
  apps: [{
    name: 'my-api',
    script: 'src/index.js',
    instances: 'max',      // use all CPU cores
    exec_mode: 'cluster',
    env: { NODE_ENV: 'development', PORT: 3000 },
    env_production: { NODE_ENV: 'production', PORT: 8080 },
    error_file: './logs/err.log',
    out_file: './logs/out.log',
    max_memory_restart: '500M'  // restart if memory exceeds 500MB
  }]
};

// pm2 start ecosystem.config.js --env production
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 77. How do you debug a Node.js application?

```bash
# 1. Built-in Node.js debugger (Chrome DevTools)
node --inspect app.js
# Then open chrome://inspect in Chrome

# 2. Break on start
node --inspect-brk app.js

# 3. VS Code debugger — add .vscode/launch.json
```

```json
{
  "version": "0.2.0",
  "configurations": [{
    "type": "node",
    "request": "launch",
    "name": "Debug Node.js",
    "program": "${workspaceFolder}/src/index.js",
    "env": { "NODE_ENV": "development" }
  }]
}
```

```js
// 4. console methods for quick debugging
console.log('Basic log');
console.error('Error:', err);
console.warn('Warning');
console.table([{ name: 'Sisi', age: 20 }]);  // tabular output
console.time('fetchUsers');
await fetchUsers();
console.timeEnd('fetchUsers'); // prints: fetchUsers: 45.3ms
console.trace('Trace stack');  // prints call stack

// 5. Debug package — log only when DEBUG env is set
const debug = require('debug')('app:server');
debug('Server started on port %d', 3000);
// Run: DEBUG=app:* node app.js
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 78. How do you handle memory leaks in Node.js?

**Common causes of memory leaks:**
- Global variables accumulating data over time
- Closures holding references longer than needed
- Event listeners not removed
- Circular references in caches
- Promises not resolved/rejected

```js
//   Memory leak — global cache grows forever
const cache = {};
app.get('/data/:id', (req, res) => {
  cache[req.params.id] = fetchExpensiveData(req.params.id);
  res.json(cache[req.params.id]);
});

//  Fix — use LRU cache with size limit
const LRU = require('lru-cache');
const cache = new LRU({ max: 500, ttl: 1000 * 60 * 5 }); // max 500 items, 5min TTL

//   Memory leak — event listener never removed
class Service extends EventEmitter {
  start() {
    process.on('SIGTERM', this.shutdown); // added on every start() call!
  }
}

//  Fix — remove listener on cleanup
start() {
  this.shutdown = this.shutdown.bind(this);
  process.on('SIGTERM', this.shutdown);
}
stop() {
  process.off('SIGTERM', this.shutdown);
}

// Monitoring memory usage
setInterval(() => {
  const { heapUsed, heapTotal } = process.memoryUsage();
  console.log(`Heap: ${(heapUsed / 1024 / 1024).toFixed(2)}MB / ${(heapTotal / 1024 / 1024).toFixed(2)}MB`);
}, 30000);

// Tools: clinic.js, heapdump, node --prof
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 79. What is microservices architecture? How does Node.js fit?

**Microservices** is an architectural style where an application is built as a collection of **small, independent services** — each responsible for a specific business capability, deployable independently, communicating over APIs or message queues.

```
Monolith:                    Microservices:
┌──────────────────┐         ┌──────────┐ ┌──────────┐ ┌──────────┐
│  Auth            │         │  Auth    │ │  Orders  │ │ Products │
│  Orders          │   →     │ Service  │ │ Service  │ │ Service  │
│  Products        │         └────┬─────┘ └────┬─────┘ └────┬─────┘
│  Payments        │              │             │             │
│  Notifications   │         ┌────▼─────────────▼─────────────▼────┐
└──────────────────┘         │         API Gateway / Message Bus     │
                             └──────────────────────────────────────┘
```

**Why Node.js is great for microservices:**
- Lightweight — fast startup, low memory per service
- Non-blocking I/O — ideal for API gateway and service communication
- npm ecosystem — rich set of tools for HTTP, messaging, gRPC
- Docker-friendly — small container images

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 80. What is serverless computing? How does Node.js work in serverless?

**Serverless** means you deploy individual functions that run on-demand — the cloud provider manages servers, scaling, and availability. You only pay for actual execution time.

```js
// AWS Lambda function (Node.js)
exports.handler = async (event, context) => {
  const { httpMethod, path, body } = event;

  if (httpMethod === 'GET' && path === '/users') {
    const users = await User.find();
    return {
      statusCode: 200,
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify(users)
    };
  }

  return { statusCode: 404, body: JSON.stringify({ error: 'Not found' }) };
};

// Vercel Serverless Function
export default async function handler(req, res) {
  if (req.method === 'POST') {
    const data = await processRequest(req.body);
    res.status(200).json(data);
  }
}
```

**Cold start problem:** First invocation can be slow (100-500ms) as the runtime initializes. Node.js has one of the fastest cold starts among runtimes.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Testing & Best Practices

<br>

### 81. How do you test a Node.js application?

**Testing layers:**

| Layer | Tool | Tests |
| ----- | ---- | ----- |
| Unit | Jest, Mocha | Individual functions, services, utilities |
| Integration | Jest + Supertest | API routes + database |
| Contract | Pact | Service-to-service contracts |
| E2E | Playwright, Cypress | Full user flows |

```js
// Unit test — pure function
// utils/math.js
const add = (a, b) => a + b;

// utils/math.test.js
describe('add()', () => {
  test('adds two positive numbers', () => {
    expect(add(2, 3)).toBe(5);
  });
  test('handles negative numbers', () => {
    expect(add(-1, 1)).toBe(0);
  });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 82. What is Jest? How do you use it for Node.js testing?

Jest is a **zero-config JavaScript testing framework** developed by Meta — supports unit testing, mocking, coverage reports, and async testing out of the box.

```js
// services/userService.js
const User = require('../models/User');

const getUserById = async (id) => {
  const user = await User.findById(id);
  if (!user) throw new Error('User not found');
  return user;
};

// services/userService.test.js
const { getUserById } = require('./userService');
const User = require('../models/User');

jest.mock('../models/User'); // auto-mock the module

describe('getUserById()', () => {
  afterEach(() => jest.clearAllMocks());

  test('returns user when found', async () => {
    const mockUser = { _id: '123', name: 'Sisi', email: 'sisi@test.com' };
    User.findById.mockResolvedValue(mockUser); // mock DB call

    const result = await getUserById('123');
    expect(result).toEqual(mockUser);
    expect(User.findById).toHaveBeenCalledWith('123');
  });

  test('throws error when user not found', async () => {
    User.findById.mockResolvedValue(null);
    await expect(getUserById('999')).rejects.toThrow('User not found');
  });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 83. What is Supertest? How do you test Express APIs?

**Supertest** is a library for testing HTTP servers — it spins up your Express app and lets you make HTTP requests in tests without actually starting a server.

```js
const request = require('supertest');
const app = require('../app'); // your Express app
const mongoose = require('mongoose');

beforeAll(async () => {
  await mongoose.connect(process.env.MONGO_TEST_URI);
});

afterAll(async () => {
  await mongoose.connection.close();
});

describe('POST /api/auth/login', () => {
  test('returns JWT token on valid credentials', async () => {
    const res = await request(app)
      .post('/api/auth/login')
      .send({ email: 'test@example.com', password: 'password123' })
      .expect('Content-Type', /json/)
      .expect(200);

    expect(res.body).toHaveProperty('accessToken');
    expect(typeof res.body.accessToken).toBe('string');
  });

  test('returns 401 on invalid credentials', async () => {
    const res = await request(app)
      .post('/api/auth/login')
      .send({ email: 'test@example.com', password: 'wrongpassword' })
      .expect(401);

    expect(res.body.error).toBe('Invalid credentials');
  });
});

describe('GET /api/users', () => {
  test('returns 401 without auth token', async () => {
    await request(app).get('/api/users').expect(401);
  });

  test('returns users list with valid token', async () => {
    const res = await request(app)
      .get('/api/users')
      .set('Authorization', `Bearer ${testToken}`)
      .expect(200);

    expect(Array.isArray(res.body.data)).toBe(true);
  });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 84. What is mocking in testing?

Mocking replaces **real dependencies** (database calls, external APIs, file system) with controlled fake implementations — making tests faster, predictable, and isolated.

```js
// 1. Jest auto-mock
jest.mock('../services/emailService');

// 2. Manual mock with jest.fn()
const sendEmail = jest.fn().mockResolvedValue({ messageId: 'abc123' });

// 3. Mock implementation
jest.spyOn(User, 'findById').mockImplementation((id) => {
  if (id === 'valid-id') return Promise.resolve({ id, name: 'Sisi' });
  return Promise.resolve(null);
});

// 4. Mock external HTTP calls with nock
const nock = require('nock');
nock('https://api.github.com')
  .get('/users/sisi-tarak')
  .reply(200, { login: 'sisi-tarak', public_repos: 20 });

// 5. Mock time
jest.useFakeTimers();
jest.advanceTimersByTime(1000); // advance time by 1 second
jest.useRealTimers();
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 85. What is the 12-Factor App methodology? How does it apply to Node.js?

The 12-Factor App is a methodology for building **scalable, maintainable, cloud-ready web applications**.

| Factor | Principle | Node.js Application |
| ------ | --------- | ------------------- |
| Codebase | One repo, multiple deploys | Git repository |
| Dependencies | Explicitly declared | `package.json` + `package-lock.json` |
| Config | Stored in environment | `dotenv`, `process.env` |
| Backing services | Treat as attached resources | DB, Redis as env var URLs |
| Build, release, run | Strictly separate stages | `npm run build` → deploy → `npm start` |
| Processes | Stateless, share-nothing | No in-memory sessions — use Redis |
| Port binding | Self-contained, export via port | `app.listen(process.env.PORT)` |
| Concurrency | Scale via process model | PM2 cluster, Kubernetes pods |
| Disposability | Fast startup, graceful shutdown | Shutdown hooks, handle SIGTERM |
| Dev/prod parity | Keep environments similar | Docker, same DB in dev and prod |
| Logs | Treat as event streams | `console.log` → stdout, ship to Datadog |
| Admin processes | One-off management tasks | DB migrations as separate scripts |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🎯 Scenario & Conceptual Questions (MNC Favourites)

<br>

### 86. Why is Node.js not suitable for CPU-intensive tasks?

Node.js runs JavaScript on a **single thread**. CPU-intensive operations (like image processing, video encoding, complex math, machine learning) **block the event loop** — preventing any other requests from being handled while the computation runs.

```js
//   CPU-intensive task on main thread — blocks everything
app.get('/compute', (req, res) => {
  let result = 0;
  for (let i = 0; i < 10_000_000_000; i++) {
    result += i; // This blocks the event loop for several seconds!
  }
  // All other incoming requests are FROZEN during this computation
  res.json({ result });
});

//  Solutions:

// 1. Worker Threads — offload to background thread
const { Worker } = require('worker_threads');
app.get('/compute', (req, res) => {
  const worker = new Worker('./compute-worker.js', { workerData: { n: 10_000_000_000 } });
  worker.on('message', result => res.json({ result }));
  worker.on('error', err => res.status(500).json({ error: err.message }));
});

// 2. Child process — spawn separate Node.js process
const { fork } = require('child_process');
app.get('/compute', (req, res) => {
  const child = fork('./compute-process.js');
  child.send({ n: 10_000_000_000 });
  child.on('message', result => res.json({ result }));
});

// 3. Dedicated microservice — offload to Python/Go service better suited for CPU tasks
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 87. What happens when you block the event loop?

When the event loop is blocked:
- **No new requests** are accepted
- **No callbacks** from completed I/O are processed
- **No timers** fire
- **The entire application freezes** until the blocking code finishes

```js
//   Synchronous JSON parsing of huge file — blocks event loop
app.get('/parse', (req, res) => {
  const data = fs.readFileSync('huge-100mb.json'); // sync read
  const parsed = JSON.parse(data.toString());      // sync parse — blocks!
  res.json({ count: parsed.length });
});

//  Always use async APIs for I/O
app.get('/parse', async (req, res) => {
  const data = await fs.promises.readFile('huge-100mb.json');
  const parsed = JSON.parse(data.toString()); // JSON.parse is still sync but much faster
  res.json({ count: parsed.length });
});

// Detecting event loop lag
const { monitorEventLoopDelay } = require('perf_hooks');
const h = monitorEventLoopDelay({ resolution: 20 });
h.enable();
setInterval(() => {
  console.log(`Event loop delay: ${h.mean / 1e6}ms`);
}, 5000);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 88. How do you scale a Node.js application?

**Vertical scaling** — add more CPU/RAM to the server.
**Horizontal scaling** — add more server instances.

```
Strategies:

1. Clustering (single server, multi-core)
   PM2: pm2 start app.js -i max

2. Horizontal scaling with load balancer
   Client → Nginx/Load Balancer → [Node Instance 1]
                                → [Node Instance 2]
                                → [Node Instance 3]

3. Containerization + Kubernetes
   - Docker containers for each service
   - Kubernetes auto-scales pods based on CPU/memory

4. Stateless design (required for horizontal scaling)
   - Sessions in Redis (not in-memory)
   - No local file storage (use S3/Cloudinary)
   - JWT over server-side sessions

5. Caching
   - Redis for DB query results
   - CDN for static assets

6. Database scaling
   - Read replicas for read-heavy workloads
   - Database connection pooling
   - MongoDB sharding
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 89. What is graceful shutdown in Node.js?

Graceful shutdown means **finishing in-progress requests before stopping the server** — instead of abruptly killing all connections, which can corrupt data or leave clients hanging.

```js
const express = require('express');
const mongoose = require('mongoose');
const app = express();

const server = app.listen(3000, () => console.log('Server started'));

// Graceful shutdown handler
async function gracefulShutdown(signal) {
  console.log(`Received ${signal}. Starting graceful shutdown...`);

  // Stop accepting new connections
  server.close(async () => {
    console.log('HTTP server closed');

    try {
      // Close database connections
      await mongoose.connection.close();
      console.log('MongoDB connection closed');

      // Close Redis, message queues, etc.
      await redisClient.quit();
      console.log('Redis connection closed');

      process.exit(0);
    } catch (err) {
      console.error('Error during shutdown:', err);
      process.exit(1);
    }
  });

  // Force shutdown after 30 seconds if graceful shutdown takes too long
  setTimeout(() => {
    console.error('Could not close connections in time. Forcing shutdown.');
    process.exit(1);
  }, 30000);
}

// Listen for termination signals
process.on('SIGTERM', () => gracefulShutdown('SIGTERM')); // Docker/Kubernetes stop
process.on('SIGINT', () => gracefulShutdown('SIGINT'));   // Ctrl+C in terminal
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 90. How do you structure a large Node.js project?

**Recommended: Layer-based + Feature-based hybrid structure**

```
src/
├── config/              # App configuration
│   ├── database.js      # DB connection
│   ├── redis.js         # Redis setup
│   └── index.js         # All config exports
├── modules/             # Feature modules
│   ├── auth/
│   │   ├── auth.controller.js
│   │   ├── auth.service.js
│   │   ├── auth.routes.js
│   │   ├── auth.middleware.js
│   │   └── auth.validation.js
│   ├── users/
│   │   ├── user.model.js
│   │   ├── user.controller.js
│   │   ├── user.service.js
│   │   └── user.routes.js
│   └── products/
├── shared/              # Shared utilities
│   ├── middleware/      # Global middleware (errorHandler, logger)
│   ├── utils/           # Helpers (pagination, format, validate)
│   └── constants/       # HTTP codes, enums
├── tests/               # Test files mirroring src structure
│   ├── unit/
│   └── integration/
├── app.js               # Express app setup (no listen())
└── index.js             # Entry point (connect DB, start server)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 91. What is the difference between monolithic and microservices architecture?

| Feature | Monolithic | Microservices |
| ------- | ---------- | ------------- |
| Codebase | Single codebase | Multiple codebases per service |
| Deployment | Deploy entire app | Deploy services independently |
| Scaling | Scale entire app | Scale individual services |
| Technology | One tech stack | Each service can use different stack |
| Failure impact | One failure can crash all | Failures are isolated |
| Communication | In-process function calls | HTTP/gRPC/message queues |
| Complexity | Lower initially | Higher initially |
| Best for | Small-medium apps, startups | Large apps, multiple teams |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 92. What is dependency injection in Node.js?

Dependency injection means **passing dependencies into a module** rather than having the module create them itself — making code more testable and loosely coupled.

```js
//   Without DI — hard to test (UserService creates its own DB dependency)
class UserService {
  async getUser(id) {
    const user = await User.findById(id); // directly depends on Mongoose
    return user;
  }
}

//  With DI — inject the repository
class UserService {
  constructor(userRepository) {
    this.userRepository = userRepository; // dependency injected
  }

  async getUser(id) {
    return this.userRepository.findById(id);
  }
}

// In tests — inject a mock repository
const mockRepo = { findById: jest.fn().mockResolvedValue({ id: 1, name: 'Sisi' }) };
const service = new UserService(mockRepo);

// In production — inject real repository
const realRepo = new MongoUserRepository();
const service = new UserService(realRepo);

// DI containers for Node.js: tsyringe, inversify, awilix
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 93. What is the difference between spawn, exec, execFile, and fork in child_process?

| Method | Use case | Output | Shell? |
| ------ | -------- | ------ | ------ |
| `spawn` | Long-running processes, streams output | Stream |   No |
| `exec` | Short commands, get full output as string | Buffer (max 1MB) |  Yes |
| `execFile` | Run executable files directly | Buffer |   No |
| `fork` | Run a separate Node.js script with IPC | IPC channel |   No |

```js
const { spawn, exec, execFile, fork } = require('child_process');

// spawn — stream large output
const ls = spawn('ls', ['-la']);
ls.stdout.on('data', data => console.log(data.toString()));

// exec — get command output as string
exec('git log --oneline -5', (err, stdout, stderr) => {
  if (err) return console.error(err);
  console.log(stdout);
});

// execFile — run a script file
execFile('node', ['script.js', '--arg'], (err, stdout) => console.log(stdout));

// fork — run Node.js file with IPC (message passing)
const child = fork('./worker.js');
child.send({ task: 'compute', data: [1, 2, 3] }); // send message to child
child.on('message', result => console.log('Result:', result)); // receive from child
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 94. What is the difference between readFile and createReadStream?

| Feature | `fs.readFile` | `fs.createReadStream` |
| ------- | ------------- | --------------------- |
| Memory usage | Loads entire file into RAM | Chunks — minimal memory |
| Speed for small files | Faster | Slightly more overhead |
| Speed for large files | Slow / may crash |  Fast |
| Suitable for | Config files, small JSON | Logs, videos, large CSVs |
| Works with pipe |   |  Yes |

```js
const fs = require('fs');

// readFile — bad for large files (loads entire file into memory)
fs.readFile('large-10gb-video.mp4', (err, data) => {
  res.send(data); //   entire 10GB in RAM before sending
});

// createReadStream — streams file in chunks
fs.createReadStream('large-10gb-video.mp4')
  .pipe(res); //  sends chunk by chunk — minimal memory

// With range support (video seeking)
const { start, end } = parseRangeHeader(req.headers.range, fileSize);
const stream = fs.createReadStream('video.mp4', { start, end });
res.status(206).setHeader('Content-Range', `bytes ${start}-${end}/${fileSize}`);
stream.pipe(res);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 95. How do you manage multiple async operations in Node.js?

```js
// 1. Sequential — one after another (slow)
const user = await getUser(id);
const orders = await getOrders(user.id);      // waits for user
const products = await getProducts(orders);   // waits for orders

// 2. Parallel — all at once with Promise.all (fast)
const [user, stats, notifications] = await Promise.all([
  getUser(id),
  getUserStats(id),
  getNotifications(id)
]); // All 3 run simultaneously

// 3. Promise.allSettled — get results even if some fail
const results = await Promise.allSettled([
  fetchFromPrimaryDB(id),
  fetchFromCacheDB(id),
  fetchFromBackupDB(id)
]);
const successful = results.filter(r => r.status === 'fulfilled').map(r => r.value);

// 4. Promise.race — get fastest result
const data = await Promise.race([
  fetchFromRegion('us-east'),
  fetchFromRegion('ap-south'),  // whichever responds first wins
  fetchFromRegion('eu-west')
]);

// 5. Batching with p-limit (control concurrency)
const pLimit = require('p-limit');
const limit = pLimit(5); // max 5 concurrent operations

const results = await Promise.all(
  userIds.map(id => limit(() => processUser(id))) // max 5 at a time
);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 96. What is NestJS? How is it different from Express.js?

**NestJS** is a **progressive Node.js framework** built with TypeScript that enforces a structured, opinionated architecture inspired by Angular.

| Feature | Express.js | NestJS |
| ------- | ---------- | ------ |
| Structure | Unopinionated — you decide | Opinionated — enforces modules, services, controllers |
| Language | JavaScript (or TS manually) | TypeScript first-class |
| DI | Manual | Built-in Dependency Injection container |
| Decorators |   |  `@Controller`, `@Injectable`, `@Module` |
| Learning curve | Low | Higher |
| Scalability | Manual organization | Built for large teams/apps |
| Under the hood | Uses raw http | Uses Express (or Fastify) underneath |

```typescript
// NestJS controller
@Controller('users')
export class UserController {
  constructor(private readonly userService: UserService) {} // DI

  @Get(':id')
  async getUser(@Param('id') id: string) {
    return this.userService.findById(id);
  }

  @Post()
  @HttpCode(201)
  async createUser(@Body() createUserDto: CreateUserDto) {
    return this.userService.create(createUserDto);
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 97. What is Fastify? How does it compare to Express?

**Fastify** is a high-performance Node.js web framework focused on speed and low overhead. It claims to be the fastest Node.js HTTP framework.

| Feature | Express | Fastify |
| ------- | ------- | ------- |
| Performance | ~15,000 req/sec | ~30,000 req/sec (2x faster) |
| JSON serialization | Manual | Built-in schema-based serialization |
| Schema validation | Manual (Joi, Zod) | Built-in (JSON Schema) |
| TypeScript | Manual setup | Built-in support |
| Plugin system | Middleware | Structured plugin system with encapsulation |
| Learning curve | Very low | Low-medium |

```js
const fastify = require('fastify')({ logger: true });

fastify.get('/users', {
  schema: {
    querystring: { type: 'object', properties: { page: { type: 'integer' } } },
    response: { 200: { type: 'array', items: { type: 'object', properties: { id: { type: 'string' }, name: { type: 'string' } } } } }
  }
}, async (request, reply) => {
  const users = await User.find();
  return users; // Fastify auto-serializes based on schema
});

fastify.listen({ port: 3000 });
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 98. What are common Node.js security best practices?

| Category | Best Practice |
| -------- | ------------- |
| **Dependencies** | Run `npm audit` regularly; use `npm ci` in CI; pin versions |
| **Environment** | Never commit `.env`; use secrets manager in production |
| **Validation** | Validate ALL user input with Joi/Zod before processing |
| **Authentication** | Use bcrypt for passwords; JWT with short expiry + refresh tokens |
| **Authorization** | Check permissions on every route; least privilege principle |
| **Rate limiting** | Limit requests per IP with `express-rate-limit` |
| **Headers** | Use `helmet` to set security headers |
| **HTTPS** | Always use HTTPS in production; redirect HTTP to HTTPS |
| **SQL/NoSQL Injection** | Use parameterized queries / ORM; never interpolate user input |
| **Error handling** | Never expose stack traces to clients in production |
| **Logging** | Log security events (failed logins, unusual activity) |
| **Updates** | Keep Node.js and packages updated |

```js
// Security middleware setup for production
app.use(helmet());
app.use(cors({ origin: process.env.ALLOWED_ORIGINS?.split(',') }));
app.use(rateLimit({ windowMs: 15 * 60 * 1000, max: 100 }));
app.use(express.json({ limit: '10kb' })); // limit request body size
app.disable('x-powered-by'); // don't reveal server tech (helmet does this too)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 99. What is the difference between setTimeout, setInterval, and setImmediate?

| Function | Runs | Use case |
| -------- | ---- | -------- |
| `setTimeout(fn, ms)` | After at least `ms` milliseconds | Delayed one-time execution |
| `setInterval(fn, ms)` | Every `ms` milliseconds | Repeated execution |
| `setImmediate(fn)` | After current I/O events, before timers | Execute after I/O in same iteration |

```js
// setTimeout — fires after ~0ms delay (minimum)
const id = setTimeout(() => console.log('Timeout!'), 1000);
clearTimeout(id); // cancel it

// setInterval — fires every 2 seconds
const intervalId = setInterval(() => {
  console.log('Tick!');
}, 2000);
clearInterval(intervalId); // stop it

// setImmediate — fires in the check phase of event loop
setImmediate(() => console.log('Immediate!'));

// Order when all three are set together (inside I/O callback):
setImmediate(() => console.log('1: setImmediate'));
setTimeout(() => console.log('2: setTimeout 0ms'), 0);
// Inside I/O: setImmediate ALWAYS before setTimeout
// Outside I/O: order is non-deterministic (depends on OS/process load)

// process.nextTick vs setImmediate:
process.nextTick(() => console.log('nextTick — runs before setImmediate'));
setImmediate(() => console.log('setImmediate — runs in check phase'));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 100. What are the new features in recent Node.js versions (v20/v22)?

**Node.js v20 (LTS) — Key Features:**

| Feature | Description |
| ------- | ----------- |
| **Stable Test Runner** | Built-in `node:test` module — no more Jest for simple tests |
| **Permission Model** | Opt-in security model to restrict file system, network, env access |
| **V8 11.3** | Improved performance, new JS features |
| **Single Executable Apps** | Bundle your app into a single binary |
| **Stable `fetch`** | Native `fetch` API (no more `node-fetch` package) |

**Node.js v22 (LTS) — Key Features:**

| Feature | Description |
| ------- | ----------- |
| **`require(esm)`** | Require ES Modules from CJS without flags |
| **WebSocket client** | Built-in `WebSocket` global (no more `ws` package for clients) |
| **`node:sqlite`** | Built-in SQLite support (no third-party package needed) |
| **`--watch` flag stable** | Built-in file watcher (replaces `nodemon` for dev) |
| **V8 12.4** | `Array.fromAsync`, `Promise.withResolvers` |

```js
// Node.js v18+ — native fetch (no node-fetch needed)
const res = await fetch('https://api.github.com/users/sisi-tarak');
const user = await res.json();

// Node.js v20+ — built-in test runner
const { test, describe, it } = require('node:test');
const assert = require('node:assert');

describe('Math', () => {
  it('adds numbers', () => {
    assert.strictEqual(2 + 2, 4);
  });
});
// Run: node --test app.test.js

// Node.js v22 — run with --watch (like nodemon)
// node --watch server.js

// Node.js v22 — built-in SQLite
const { DatabaseSync } = require('node:sqlite');
const db = new DatabaseSync(':memory:');
db.exec('CREATE TABLE users (id INTEGER, name TEXT)');
```

**[⬆ Back to Top](#table-of-contents)**

<br>
<br>

<div align="center">

## 🎉 You've covered all 100 Node.js Interview Questions!

**If this repo helped you prepare, please give it a ⭐**

[![Star this repo](https://img.shields.io/github/stars/sisi-tarak/nodejs-interview-questions?style=social)](https://github.com/sisi-tarak/nodejs-interview-questions)



### 📲 Follow Sisi for more tech interview prep content

[![Instagram](https://img.shields.io/badge/Instagram-%40sisi__tarakk-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sisi_tarakk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sisindri%20Singamsetti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sisitarak)
[![GitHub](https://img.shields.io/badge/GitHub-sisi--tarak-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sisi-tarak)

---

### 🤝 Want to contribute?

Found a mistake, have a better explanation, or want to add more questions?

**[Open a Pull Request](https://github.com/sisi-tarak/nodejs-interview-questions/pulls)** — all contributions are welcome! 🙌

---

### 📦 More Interview Repos

| Status | Repository |
| ------ | ---------- |
|  Live | [react-interview-questions](https://github.com/sisi-tarak/react-interview-questions) |
|  Live | [nodejs-interview-questions](https://github.com/sisi-tarak/nodejs-interview-questions) |
| 🔜 Coming | mern-interview-questions |
| 🔜 Coming | dsa-interview-questions |
| 🔜 Coming | java-interview-questions |
| 🔜 Coming | python-interview-questions |

⭐ **Star this repo to get notified when new repos drop!**

---

## Disclaimer

The questions in this repository are compiled from frequently asked interview questions across MNC companies including TCS, Infosys, Wipro, Cognizant, HCL, Capgemini, Accenture, Amazon, Flipkart, and other product companies. We cannot guarantee these exact questions will appear in your interview. The goal is to build conceptual clarity, not memorization.

Good luck with your interview! 😊

*Made with ❤️ by [Sisi](https://instagram.com/sisi_tarakk) | Helping Telugu tech students crack their dream jobs 🚀*

</div>
