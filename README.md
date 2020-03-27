# Wordpress Config

## Setup

Download a copy of Wordpress and deploy it to a web server of your choice. Git clone this repo into the root of the
Wordpress installation and follow the steps below.

`bash composer install`

## Configuration

Create a copy of .env.example and fill provide the required values.

## Local Infrastructure

Update the configured ports for TLS termination in `docker-compose.yml` to suit your local web server configuration and
local domain configuration. Bring up local instances of MySQL and Adminer, as well as TLS termination.

```bash
docker-compose up
```
