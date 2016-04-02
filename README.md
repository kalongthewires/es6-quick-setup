# es6-quick-setup

## Getting started

```
npm install
```

## Running Babel

Compile your ES2015 JS to ES5 with Babel using:
```
npm run build
```

## Running server

Run the server to view your code on http://localhost:3000:
```
npm start
```

Note: an error will occur if the port is already in use. If you encounter issues, try changing the port number in package.json under "scripts":

```
"start": "http-server . -o -p 8080",
```