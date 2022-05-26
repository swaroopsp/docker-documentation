## docker-documentation

## Maven JIB command
# mvn compile jib:build
# mvn compile jib:dockerBuild

## Running docker image
# docker run -p 8080:8080 7d8b7fc47d4e

## Get in to the docker image
# docker exec -it 33980f871780 sh


## Remove all the images/container
# docker rm -vf $(docker ps -aq)
# docker rmi -f $(docker images -aq)
# docker system prune -a --volumes


#https://stackoverflow.com/questions/53669151/java-11-application-as-lightweight-docker-image
