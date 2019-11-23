# DOCKER POSTGRESQL

Create docker image

```
docker-compose up
```

Connect to the container shell

```
docker-compose run database bash
```

Connect to the database

```
psql --host=database --username=sudhir --dbname=xxxxxxx
```

To destroy all volumes with containers down

```
docker-compose down --volumes
```
