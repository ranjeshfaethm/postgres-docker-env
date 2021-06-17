# postgres-docker-env
postgres-docker-env is a repo to setup docker images of postgres and pg-admin

### running postgres and pg-admin in docker
On root
```bash
docker-compose up --build
Or docker-compose up
```
This will run postgres database and pg-admin in docker.
If a new docker image is created, script/init contains files for table creation '1-schema.sql' and table data initialisation '2-data.sql'.
