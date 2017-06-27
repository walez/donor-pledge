# DonorMgt

The app shows how to use ArcGis javascript library with Angular2 and above using socket.io for realtime update of map markers.

Live demo at https://donor-pledge.herokuapp.com/

## Development setup

Run `npm install` to install client and server dependencies.
Insert MongoDB connection url in `default.json` and `test.json` file in `config` folder.

Run `ng build aot` to build a static version that can be served from the express app.

## Run Project

Run `npm run start` to start up the Development server.
Vist localhost:3000 (unless the PORT has been specified in the env) to use the app

## Running unit tests

Run `npm run test-client` to execute the client side unit tests via [Karma](https://karma-runner.github.io).
Run `npm run test-server` to execute the server side unit tests via Mocha.

