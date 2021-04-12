# Dockerize Vue.js + NodeJs

## How to run with docker-compose

### Fetch project and sub projects.

First of all read [Git tools - submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules).
You must run:

    git submodule update --init --recursive

to initialize your local configuration file and fetch all the data from the sub projects.

## Environment variables

Next, copy .env.example into .env file inside backend project and set the environment variables:

    cp nodejs-express-sequelize-mysql/.env.example nodejs-express-sequelize-mysql/.env

## Run project

To run project use:

    docker-compose up --build -detach

## Documentation base projects

For instruction, please visit:
> [Vue.js CRUD App with Vue Router & Axios](https://bezkoder.com/vue-js-crud-app/)

More Practice:
> [Vue Pagination with Axios and API example](https://bezkoder.com/vue-pagination-axios/)

> [Vue.js JWT Authentication with Vuex and Vue Router](https://bezkoder.com/jwt-vue-vuex-authentication/)

> [Vue File Upload example using Axios](https://bezkoder.com/vue-axios-file-upload/)

Fullstack with Node.js Express:
> [Vue.js + Node.js Express + MySQL](https://bezkoder.com/vue-js-node-js-express-mysql-crud-example/)

> [Vue.js + Node.js Express + PostgreSQL](https://bezkoder.com/vue-node-express-postgresql/)

> [Vue.js + Node.js Express + MongoDB](https://bezkoder.com/vue-node-express-mongodb-mevn-crud/)

Fullstack with Spring Boot:
> [Vue.js + Spring Boot](https://bezkoder.com/spring-boot-vue-js-crud-example/)

> [Vue.js + Spring Boot + MongoDB](https://bezkoder.com/spring-boot-vue-mongodb/)

Fullstack with Django:
> [Vue.js + Django](https://bezkoder.com/django-vue-js-rest-framework/)

Integration (run back-end & front-end on same server/port)
> [Integrate Vue.js with Spring Boot](https://bezkoder.com/integrate-vue-spring-boot/)

> [Integrate Vue App with Node.js Express](https://bezkoder.com/serve-vue-app-express/)

Serverless with Firebase:
> [Vue Firebase Realtime Database: CRUD example](https://bezkoder.com/vue-firebase-realtime-database/)

> [Vue Firestore CRUD example](https://bezkoder.com/vue-firestore-crud/)