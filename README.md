IRIS In One Command
===

This repo lets you quickly start and use the following services:

1. iris-api
2. iris-relay
3. iris-frontend
4. iris-sender
5. iris-admin
6. mysql

Getting started
---

Spin up the cluster

    make

Start your web browser and go to: http://localhost:16649

Stop the stack..

    docker-compose stop

Start it again without recreating everything:

    docker-compose up --no-recreate

Poking around
---

See which containers are running:

    docker ps

Jump into a container:

     docker exec -i -t $ID  /bin/bash

Kill a container

    docker rm -f $ID
    

Iris-Admin
---

Append iris-admin in docker-compose.yml from phamlamvuong/iris-admin:0.0.1 image.
