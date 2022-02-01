# CQRS and DDD Symfony 5 Boilerplate

A ready-to-use skeleton project on Symfony 5 using the best practiques for CQRS and DDD running with PHP 8, Nginx as Webserver, Postgres as database, working with Elastic and messaging queue with RabbitMQ. For the front end includes React and Webpack optional integration.

### Features

- [ ] Dockerized Environment
- [ ] Symfony Messenger
- [ ] Event Store
- [ ] Read Model
- [ ] Async Event subscribers
- [ ] Rest API
- [ ] Event Store Rest API
- [ ] Swagger Open API Documentation
- [ ] React Web UI (optional)

# How to start

|    Action        	|     Command    |
|------------------	|---------------	|
|  Setup 	          | `make start`   |
|  Run Tests       	| `make phpunit` |
|  Static Analisys 	| `make style`  	|
|  Code Style      	| `make cs`     	|
|  Code style check	| `make cs-check`|
|  PHP Shell 	      | `make s=php sh`|
|  Xdebug 	         | `make xoff/xon`|
|  Build Artifacts   | `make artifact`|

# Architecture