# Laravel docker horizon

Is my own implementation to my Laravel API projects. Execute horizon and scheduler.

```
userId: 1000
user: laravel
php: 8.0
```

## Build the image and name it

```shell
docker build --tag laravel-docker-horizon .
```

## Login to docker hub

```shell
docker login
```

## Tag the image

```shell
docker tag laravel-docker-horizon jncalderon/laravel-docker-horizon:1.0
```

## Push the image to repository

```shell
docker push jncalderon/laravel-docker-horizon:1.0
```

## Verify repository exists

```shell
https://hub.docker.com/r/jncalderon/laravel-docker-horizon
```
