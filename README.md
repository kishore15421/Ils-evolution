# Evolutions_WebApp
Main Web App for the Dynamo Evolutions Front End Web Application

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js and npm](nodejs.org) Node ^8.9.0, npm ^5.5.1

### Developing

1. Run `npm install` to install dependencies.
2. Run `npm run lint` to start eslint.
3. Run `npm start` to start the development server.
4. Open http://localhost:8080 in browser

## Build & development

Run `npm run build` for building (build will store in /dist folder).
Run `npm run deploy` for deploy to remote server (should be config in .env file).

## To Build and Deploy Manually via sFTP

Run npm run build for building (build will store in /dist folder). Connect via sFTP using .PEM or .PPK file Remove all content from “/home/ubuntu/www2” then upload content from local “/dist”

## Configuration

Update /src/config.js BASE_URL variable to change the endpoint

## Demo frontend
1) evolutions.dukucrm.com (customer 1) Username: jdoe_evolutions Pwd: demo
2) pm2.dukucrm.com (customer 2) Username: jdoe_pm2 Pwd: demo

## Backend
https://evolutions-dev-api.dukucrm.com/ 

## Local frontend hosts 
`/etc/hosts`
127.0.0.1 evolutions.localhost pm2.localhost
#   I l s - e v o l u t i o n  
 