[![Run on Repl.it](https://repl.it/badge/github/JscramblerBlog/express-mongoose-api)](https://repl.it/github/JscramblerBlog/express-mongoose-api)
MongoDB Mongoose Relationships
=====

> This is a lightweight starter boilerplate for getting started with MEAN stack apps (MongoDB, Express, Angular, Node.js). In it you can configure environment variables, define models and set up api routes. It is lightweight and much easier to grok than mean.io or mean.js.

> If you are looking for a solution for authentication check out [this repo](https://github.com/cleechtech/node-jwt-intro).

### Getting started
```
$ git clone <this_repo_url>
$ cd mean-starter
$ npm install
$ npm run start
```

### Deploy to Heroku
```
heroku create <app_name>
heroku config:set NODE_ENV=production
heroku addons:create mongolab:sandbox 
heroku config | grep MONGOLAB_URI
git push heroku master
heroku ps:scale web=1
```
