# EzLogger-Setup
This is a simple setup for creating the server side environment for the library `ng-ez-logger` : https://www.npmjs.com/package/ng-ez-logger

This setup will be  downloading docker images for an logger `API` and  a logger  `web viewer`
API : https://github.com/ezlogger/EzLogger-API
Viewer : https://github.com/ezlogger/EzLogger-Viewer

## Instructions

- Clone or download the docker-compose file in this repo
- Run `docker-compose up`  command

##  Log Viewer details
After executing `docker-compose up` , the log viewer will be running on `http://localhost:3000`

## API details

After executing `docker-compose up` , the log API will be running on `http://localhost:5000`

The swagger for the API can be accessed by this link `http://localhost:5000/api/index.html?url=/api/specification.json`
