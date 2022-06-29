# DOCKER DJANGO EXMAPLE

## Steps

1. Create APP in heroku with necessary resources

2. Set environment variables in heroku panel

## Command to build image locally with specific name

``` docker build -t docker_heroku:v1 .```

## Commands to push to app

* Will make new image and container based on DockerFile

```heroku container:push web -a=zahur-docker```

```heroku container:release -a zahur-docker web```

