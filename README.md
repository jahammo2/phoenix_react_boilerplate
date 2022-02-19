# WhatsappInactiveMembersHandler

## TODOS

* [x] run a successful frontend build
* [x] start a successful frontend dev server
* [x] deploy successful frontend code
* [x] rewrite src to its own file structure
* [x] get FE tests passing
* [x] remove unnecessary scripts in package.json
* [x] get styles to pass between prod and dev
* [x] decide on assets/js and assets/vendor
* [x] write 1 exunit test for something basic
* [x] write 1 Cypress test

* [ ] write basic documentation for getting started
* [ ] turn this into a boilerplate

* [ ] write 1 test taking .txt file contents and doing things
* [ ] do a little product planning
* [ ] rewrite all "costing request" stuff over to relevant stuff
* [ ] write tests for all backend work

## Getting started

1. `mix deps.get`
1. `yarn install`
1. `mix ecto.setup`
1. `mix phx.server`
1. `yarn watch`
1. visit http://localhost:4000
1. https://hexdocs.pm/phoenix/heroku.html
1. Add these buildpacks (in order I think):
    * https://github.com/HashNuke/heroku-buildpack-elixir
    * https://github.com/gjaldon/heroku-buildpack-phoenix-static

### Questions

* What can outside users do?
* What instructions will I add to the frontend

## How to...

### Build the frontend

`yarn build`

### Watch the frontend

In a separate tab, `yarn watch`

### To deploy

`git push heroku master`

### Run E2E tests

1. `mix phx.server`
2. `yarn watch`
3. `yarn run cypress open`
