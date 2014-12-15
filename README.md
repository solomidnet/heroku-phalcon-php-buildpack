# Heroku buildpack: Phalcon

This is a fork of the official [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for PHP applications. It supports [Phalcon](http://phalconphp.com/) and Node.js.

For further information, refer to [original buildpack](https://github.com/heroku/heroku-buildpack-php) and Thien Tran Duy's [original article](http://www.sitepoint.com/install-custom-php-extensions-heroku/).

## Usage

All you have to do is require Phalcon in your `composer.json`:

```json
{
  "require": {
    "ext-phalcon": ">=1.3.0"
  }
}
```