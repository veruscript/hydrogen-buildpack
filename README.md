Veruscript Hydrogen - Custom Buildpack for Heroku
=================================================

A buildpack consists of three scripts:

    bin/detect: Determines whether to apply this buildpack to an app.
    bin/compile: Used to perform the transformation steps on the app.
    bin/release: Provides metadata back to the runtime.

 - https://devcenter.heroku.com/articles/buildpack-api

