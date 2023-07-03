# PostgREST with Docker

A simple project to work out how PostgREST and Docker work together.

## Start

`docker-compose up`

This command will start a Postgres db container on port 5432 and the PostgREST container on port 3000.

The first time this is called it will pull down the images and run the sql scripts in the initdb/ folder.
