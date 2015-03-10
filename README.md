# Blox

[![Build Status](https://travis-ci.org/drewolson/blox.svg?branch=master)](https://travis-ci.org/drewolson/blox)

It's a blog?!

## Setup

```bash
mix do deps.get, db.reset
npm install
```

## Run it

```bash
mix phoenix.server
```

## Test it

```bash
MIX_ENV=test mix db.reset
mix test
```

## Assets

Phoenix will use `brunch` to compile assets when you run `mix phoenix.server`. If you'd like to manually compile the assets, run `npm run build`.

## Assumptions

Blox assumes you're running postgres locally on the default port and that your current user can create databases.
