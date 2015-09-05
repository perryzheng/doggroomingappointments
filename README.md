# Dog grooming appointments app

## Running Locally

Make sure you have Play and sbt installed.  Also, install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

```sh
$ sbt compile stage
$ foreman start web
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku
```sh
$ heroku create
$ git push heroku master
$ heroku open
```
