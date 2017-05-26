# [Heroku Buildpack for Stack and Elm][1]

[Heroku buildpack][2] for [Stack][3] and [Elm][4]. Based on the excellent [heroku-buildpack-stack][5] and [heroku-buildpack-elm][6]

### Usage

Create an app with this buildpack:

    $ heroku create --buildpack https://github.com/ott8bre/heroku-buildpack-stack-elm.git

Set this buildpack on an existing app:

    $ heroku buildpacks:set https://github.com/ott8bre/heroku-buildpack-stack-elm

[1]: https://github.com/ott8bre/heroku-buildpack-stack-elm
[2]: http://devcenter.heroku.com/articles/buildpacks
[3]: https://github.com/commercialhaskell/stack
[4]: http://elm-lang.org
[5]: https://github.com/mfine/heroku-buildpack-stack
[6]: https://github.com/srid/heroku-buildpack-elm
