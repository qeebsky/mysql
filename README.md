# Initialize MySQL schema for the first time

1. Put .sql files into mysql/initdb.d/
2. Build MySQL container

# Start MySQL server

```sh
docker-compose up -d
```

# Quick connect to MySQL server

```sh
mysql -h 127.0.0.1 -u root -p root
```

# For more information

https://hub.docker.com/_/mysql/
