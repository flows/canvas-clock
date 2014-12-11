# Canvas Clock

Install graph dependencies:
`fbpx install graphs/clock.fbp`

`fbpx browserify graphs/clock.fbp > example/bundle.js`

Watch:
`fbpx browserify graphs/alert.fbp --watch -o example/bundle.js`

Watch and reload with fb-flo:

`fbpx browserify graphs/alert.fbp --watch --browser -o example/bundle.js`

Server index.html
`http-server example/`
