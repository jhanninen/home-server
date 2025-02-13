# Home server configurations

This repository contains configurations to set up home server apps using Docker. The main motivation to use Dockerized method to set up the server is to have back up of configurations and make recreation of the server easier.

## Prerequisites

Docker and Docker Compose needs to be installed on the server.

## Usage

Create an env file and configure it.

```
cp .env.example .env
```

Start the apps:

```
docker compose up -d
```
