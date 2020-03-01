FROM openjdk:8-alpine
COPY target/rest-service-0.0.1-SNAPSHOT.jar /usr/local/app/
WORKDIR /usr/local/app/
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "rest-service-0.0.1-SNAPSHOT.jar"]