GeoJSON Proxy
=============

A small app to demonstrate converting arbitrary JSON in to GeoJSON for consumption by GIS applications.

Supports JSON APIs that return either an `items` or `item` response property. 

Each object should have a `lat` and `long` value.

## Try it out at

- [/api?endpoint=<url_on_target_file>](https://bcns.ai/DR5AMS)

or

- [https://json-to-geojson.herokuapp.com/api?endpoint=<url_on_target_file>](https://json-to-geojson.herokuapp.com/api?endpoint=bit.ly/simple-json)

## Resources

- [CodeSandbox — Docs](https://codesandbox.io/docs/learn)
- Add your [configuration](https://codesandbox.io/docs/projects/learn/setting-up/tasks) to optimize it for [CodeSandbox](https://codesandbox.io/p/dashboard)

## Connection with a developer

[![Telegram](https://img.shields.io/badge/Telegram-Group-blue.svg?logo=telegram)](https://telegram.me/developer_support_bot)

## Deploy using Heroku Button

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Deploy using Heroku Git

### Install the Heroku CLI

Download and install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-command-line).

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.
```
$ heroku login
```
or
```
$ heroku login -i
```

### Clone the repository

Use Git to clone application source code to your local machine.
```
$ heroku git:clone -a APP_NAME
$ cd APP_NAME
```

### Deploy your changes

Make some changes to the code you just cloned and deploy them to Heroku using Git.
```
$ git add .
$ git commit -am "make it better"
$ git push heroku master
```

### Downloading the application slug

If you have not used git to deploy your application, or using `heroku git:clone -a APP_NAME` has only created an empty repository, you can download the slug that was build when you application was last deployed. 

First, install the [heroku-slugs](https://github.com/heroku/heroku-slugs) CLI plugin with `heroku plugins:install heroku-slugs`, then run:
```
$ heroku slugs:download -a APP_NAME
```
