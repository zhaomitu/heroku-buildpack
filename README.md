Heroku buildpack: CasperJS
=======================

This is based on the example [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks).

Usage
-----

Example usage:

    $ ls
    casperjs.txt

    $ heroku create --stack cedar --buildpack http://github.com/ck86/heroku-buildpack-casperjs.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> CasperJS app detected
    -----> Found a casperjs.txt

The buildpack will detect that your app has a `casperjs.txt` in the root.
