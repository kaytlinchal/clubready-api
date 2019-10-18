# ClubReady API



## Getting Started

Set up a Sentry account to maintain error logging, in the settings.py file, simply add sentry token. Sentry is free on a base account.

## Architecture

The architecture of this project was standard to the python/Fast api documenetation. Only thing to look for is that the celery tasks are added in the exchange directory.

## Prerequisites

Installing Docker on the machine that is in use. Go to website and install the software, and then run the docker commands to build the software.

## Deployment

To Build this project, the machine must have Docker installed. To build, change into the file directory, and run the following command:

```
docker-compose up --build
```



## Built With

* [Flask](http://flask.pocoo.org/) - The web framework used
* [Docker](https://www.docker.com/) - Development and delivery of software inside standardized containers.

## Authors

* ** Kaytlin Chaloner ** - *Developer* - [github](https://github.com/kaytlinchal)

## Acknowledgments

* The structure of this code was from a project I had previously built.
* Inspiration for the architecture was Asynchronous deployment.