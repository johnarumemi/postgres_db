# PostgreSQL Docker Compose
Currently uses pgsql version 12. <br>

### Environment Variables
requires following environment variables,

+ PGSQL_PASSWORD : This sets the password to access the server running in the docker container.

### Volumes
+ postgres_db-database : mounted to /var/lib/postgressql/data


<br><br>
See this [link][1] for more settings that can be passed to the image used as the base.


[1]: https://hub.docker.com/_/postgres "PostreSQL Docker Image"
