FROM openjdk:8-jre-alpine

LABEL maintainer="Olwyn Meek ojmeek@gmail.com"

EXPOSE 8080

WORKDIR /usr/local/bin

COPY maven/fleetman-0.0.1-SNAPSHOT.jar /usr/local/bin/webapp.jar

CMD ["java", "-Dspring.profiles.active=docker-demo", "-jar", "webapp.jar"]
