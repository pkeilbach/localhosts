# localhosts
A collection of docker-compose files for various local servers.

## Prerequisites

The docker network is declared as external, so the network needs to be created manually:

```sh
docker network create pk17_localhosts
```

## Usage

Make sure to specify the compose file when launching a service, e.g. redis:

```sh
docker-compose -f redis.yml up -d
```

## Useful Links

Use pre-existing networks: https://docs.docker.com/compose/networking/#use-a-pre-existing-network

## TODO
- add env files
- elastic
- mongodb
- neo4j
- postrges
