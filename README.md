<p align="center">
  <a href="https://tonystrawberry.codes/">
    <img src="https://cdn-icons-png.flaticon.com/256/4388/4388554.png" width="60" />
  </a>
</p>
<h1 align="center">
  Quote Editor (powered by Hotwire)
</h1>

[![Coverage Status](https://coveralls.io/repos/github/tonystrawberry/quote-editor/badge.svg)](https://coveralls.io/github/tonystrawberry/quote-editor)


This application is a simple quote editor that allows users to create, edit, and delete quotes. I followed the tutorial from [Hotrails](https://www.hotrails.dev/turbo-rails) to build this application. The tutorial has been a great introduction to **Hotwire** and how to use it to make an **SPA with Rails without using JavaScript**.

Deployed with **Fly.io** https://quote-editor-cool-snow-3844.fly.dev/

## Setup ⚙️

```
  bundle install
  rails db:create db:migrate db:seed
```

## Running the application 🚀

```
  bin/dev
```

## Running the tests 🧪

```
  bin/rails test:all
```

## Test accounts

Test accounts can be found in the `test/fixtures/users.yml` file. Please use the credentials in that file to log in.
