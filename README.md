# imears-server [![CircleCI](https://circleci.com/gh/iMears/imears-server.svg?style=svg)](https://circleci.com/gh/iMears/imears-server)

This app was generated using the Rails `--api` flag and therefore is a JSON API only.

### Getting started

You’ll need to have Ruby >= 2.2.0 on your machine.
You can use rvm to easily switch Ruby versions between different projects.


### Installing

```bash
  git clone git@github.com:iMears/imears-server.git
  cd imears-server
  bundle install
```


### Setup Database

```
  rake db:create
  rake db:migrate
```

### Starting Rails server

```bash
  rails server
```

- http://localhost:3000/v1/ endpoints should now respond with JSON when api_key is valid.


### Running tests

```bash
  rspec spec
```

