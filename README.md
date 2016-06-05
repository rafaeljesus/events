# Events

[Events]() is a modular microservices in node.js, mongodb, rabbitmq, docker.

### events-api

[events-api](https://github.com/rafaeljesus/events-api) is the http api that's
responsible for serving a search API. It responds to different HTTP endpoints and
uses [events-core](#events-core).
repository.

### events-core

[events-core](https://github.com/rafaeljesus/events-core) holds the event model.
This repository is shared across [events-api](#events-api) and [events-worker](#events-worker).

### events-util

[events-util](https://github.com/rafaeljesus/events-util) Events utilities shared by [events-api](#events-api) and [events-worker](#events-worker)

### events-worker

[events-worker](https://github.com/rafaeljesus/events-worker) receives
events from rabbitmq and stores out data to mongodb.

### events-ui

[events-ui](https://github.com/rafaeljesus/events-ui) is the [React](https://github.com/facebook/react) and [Flux](https://github.com/facebook/flux) web client for Events API and communicates with [events-api](#events-api) to get information.
