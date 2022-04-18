# WordPress With Docker

A quick WordPress development environment run on Docker.

### Getting started

1. Install docker [https://docs.docker.com/get-docker](https://docs.docker.com/get-docker)
2. Pull this repository `git clone git@github.com:tranquangvu/wordpress-with-docker.git your-app-name && cd your-app-name`
3. Run `docker-compose up -d` to start the container
4. Visit http://localhost:8080
5. Proceed and complete WordPress installation
6. Your website is ready to be developed to its next awesome level

- Notes:
  - WordPress: http://localhost:8080
  - PhpMyAdmin: http://localhost:8081
  - MySQL: goldenowl/password

## Docker Compose Commands

- `docker-compose up` to start the container
- `docker-compose up -d` to start the container in the background
- `docker-compose down` to stop the container
- `docker-compose build` to rebuild the container

See this for further reference on `docker-compose`, https://docs.docker.com/compose/reference/
