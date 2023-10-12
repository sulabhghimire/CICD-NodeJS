# Simple Web App

This is a simple NodeJs web app built on top of express.js framework to test CI/CD process.

## Setup

Setup is as simple as:

```bash
npm install
# Run unit tests
npm run test
# Run the app
npm run start
```

TO run the docker container do:
 - docker build . -t sulabh/node-web-app:v1
 - docker run -d -p 8001:5000 sulabh/node-web-app:v1
