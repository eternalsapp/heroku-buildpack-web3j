# Heroku Buildpack Web3j

This is a [Heroku Buildpack](https://devcenter.heroku.com/articles/buildpacks)
that install the latest production version of [Web3j CLI](https://docs.web3j.io/4.8.7/command_line_tools/)

## Usage

Set up the Buildpack in your app:
```bash
heroku config:add BUILDPACK_URL=https://github.com/eternalsapp/heroku-buildpack-web3j --app <app>
```

Then create a file called `.web3j` in the project root directory in order to let heroku know that you want web3j to be installed

## See also

- [Using multiple buildpacks for an app](https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app)
- [Web3j](https://web3j.io)

