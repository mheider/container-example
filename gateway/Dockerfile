FROM openjdk:8-jdk-alpine
VOLUME /tmp
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
COPY target/gateway.jar app.jar
