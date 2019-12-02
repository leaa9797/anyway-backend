# anyway-backend


------

# ANYWAY’s docker environment
-----------------------

Read more about DOCKER at [Offical docs](https://docs.docker.com/) or at [Github project] (https://github.com/docker/docker)


Instructions
-----------------------
* Please complete ANYWAY’s [“getting the code” section] (https://github.com/hasadna/anyway#getting-the-code-and-adding-ci-to-your-forked-repository) before starting

**1.** [Get the code] (https://github.com/hasadna/anyway#getting-the-code-and-adding-ci-to-your-forked-repository)

**2.** [Install Docker] (https://docs.docker.com/install/)

**3.** Open "Docker terminal", go to the **anyway** directory and run:
    `docker-compose up`

**4.** **You're all set!** ANYWAY is up and running - go to http://127.0.0.1:5000 **Now you only need to load the data :)***


### FYI

There are 2 Dockerfiles in this project :
1) The PostgreSQL DB docker at the "db_docker" folder
2) The actual application docker is the Dockerfile



#### ReBuild & ReRun
If you change the docker files and want to re-run the docker-compose you need to:

`docker-compose build` and then: `docker-compose up`


docker-postgis - Dockerfile, initdb-postgis.sh and update-postgis.sh where taken from here:
`https://github.com/appropriate/docker-postgis/tree/f6d28e4a1871b1f72e1c893ff103f10b6d7cb6e1/10-2.4`
