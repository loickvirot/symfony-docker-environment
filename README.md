# Symfony docker-compose template

Template to host Symfony applications on docker with PHP and MySQL

This template uses :

- PHP version: 8.3
- Nginx version: latest version in alpine packages
- MySQL version: 8.3
- Composer: 2.7
- Node: 21 (useful for webpack-encore, remove it if you don't need it.)

This template comes with some tools :

- PHPCS
- PHPStan
- PHPUnit
- Github Workflow to run these tools for each push

## Requirements

To use this template, you need to have these programs installed :

- Docker
- Docker Compose

## Run composer

You can use this command to run composer:

```bash
docker-compose run --rm composer --version
```

## Run nodeJS

You can use this command to run node:

```bash
docker-compose run --rm node node --version
docker-compose run --rm node npm --version
```
