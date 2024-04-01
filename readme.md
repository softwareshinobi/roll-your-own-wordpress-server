# Valorant Digital Wordpress

a customized wordpress docker image with some salt, pepper, and a little sauce on top.

the base wordpress docker image sucks. this sucks a little less.

## current modifications

* none.

## future modifications

* enable API automatically

* enable API automatically

* increase max file upload size

* increase max process wait time

* remove 2024 theme

* remove 2023 theme

* install neil patel plugins

* install wpvivid

## god tier

create a companion container to do the database export

create a companion container to do the wordpress file export

## how to do it

build the image to spec (see Dockerfile)

```
docker build . -t softwareshinobi/valorant-digital-wordpress
```

log in to dockerhub

```
docker login # use your dockerhub credentials
```

push to dockerhub

```
docker push  softwareshinobi/valorant-digital-wordpress
```

## or run it

will do everything and push to dockerhub.

```
bash push.bash
```

This repository doesn't have an overview

## Docker Pull Command

```
docker pull softwareshinobi/valorant-digital-wordpress
```

##  coming soon

full docker compose. im just moving fast right now.

## see the docker image in docker hub

https://hubs.docker.com/r/softwareshinobi/valorant-digital-wordpress
