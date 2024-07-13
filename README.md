fixie-wrench-example-app
===============

This is a simple app demonstrating how to use `fixie-wrench`. In this example, HTTP requests to `worldclockapi.com` are proxied though a local port on the Heroku application instance via `fixie-wrench` and then through Fixie Socks.

The same approach can be used to proxy database connections or any other TCP connection.

For more information, see the [fixie-wrench documentation](https://github.com/usefixie/fixie-wrench).

## Deploy to Heroku

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Deploy to Koyeb

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&name=fixie-wrench-example-app&repository=github.com/usefixie/fixie-wrench-example-app&branch=add-koyeb-support&ports=8080;http;/&)

