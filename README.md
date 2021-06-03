# <img src="https://raw.githubusercontent.com/kien123456k/task-management-frontend/master/public/favicon.ico" width="50" height="50"/> - Task Management API

## What is Task Management API?
The API for a web application that may save you from missing tasks.
But this is still a simple one.

Here is [the Frontend](https://github.com/kien123456k/task-management-frontend) that using this API

`The more full feature is comming soon!`
## Technology
- Frontend
  - React - A JavaScript library for building user interfaces
  - Create React App - React starter template
  - MobX - State Management
  - Material UI - UI components
  - Styled-components - Styling
  - Typescript - Static Type Checker
- Backend
  - NestJS - Server Core
  - Mongoose + MongoDB - Database

## Installation Dependencies

```bash
$ yarn install
```

## Running the app
First, you shoud create development.yml or production.yml in config folder to override default environment variable in default.yml to suit your host configuration.

```bash
# development (development.yml)
$ npm run start

# watch mode (development.yml)
$ npm run start:dev

# production (production.yml)
$ npm run start:prod

# docker
$ docker-compose up -d
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

# License & copyright

© Kirin Tran, FPT University TP.HCM
Licensed under the [MIT LICENSE](LICENSE).
