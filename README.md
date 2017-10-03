# MySQL instance

This is a quick run of mysql with init dump file. It can help you quickly start a mysql with a init data.

## Init mysql

Put the dump file into db-init, and run use docker-compose.yaml. 

## Build with init dump file

If you want to build the db using init dumpfile, you can build using:

```
docker build -t test/mysql .
```


