FROM openjdk:16-alpine3.13
MAINTAINER John Cena<john@gmail.com>
VOLUME /tmp
EXPOSE 8080
ARG JAR_FILE=target/websocket-demo-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} websocket-demo.jar
ENTRYPOINT ["java","-jar","/websocket-demo.jar"]
