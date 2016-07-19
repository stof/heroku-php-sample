# Test Application for my Heroku Buildpack

## Deploy

Create a new Heroku app:

```bash
$ heroku create <name> --buildpack heroku/php
$ heroku config:set HEROKU_PHP_PLATFORM_REPOSITORIES=https://incenteev-heroku-php-exts.s3.amazonaws.com/dist-cedar-14-develop/packages.json
```

Deploy:

```bash
$ git push heroku master
```
