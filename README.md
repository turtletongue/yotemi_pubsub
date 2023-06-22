## How to run the service

You can use docker-compose to start service easily.

First of all, install [docker-compose](https://docs.docker.com/compose/install/) if you don't have it on your machine. Make sure you follow all prerequisites.

Secondly, you must create .env file in the root folder with content like this:

```dotenv
REDIS_PASSWORD=strong_redis_password
```

Now, you can execute this command:

```shell
# build containers and run application
docker-compose up
```

If you want to stop containers, just use:

```shell
docker-compose stop
```

If you want to remove containers, use:

```shell
docker-compose down
```