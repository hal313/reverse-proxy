# reverse-proxy

> This is part of the ["standard development environment" example ](https://github.com/hal313/standard-development-environment-example). See that page for more information.

## Purpose

The reverse proxy container for the standard development environment. Responsible for:

1. Displaying a welcome page to the user
2. Directing requests from the client machine to the correct containers

This container is typically not altered by the user, though manual intervention is currently required in order to support multiple environments on the same host, due to container naming collisions. See:

- [GitHub issue](https://github.com/hal313/reverse-proxy/issues/1)
- [Explanation](https://github.com/hal313/dev-env#todo)
