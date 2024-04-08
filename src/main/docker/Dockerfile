FROM openjdk:17-jdk-alpine
ADD target/spring-cloud-gateway-sample-0.0.1-SNAPSHOT.jar spring-cloud-gateway.jar
EXPOSE 8080
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/spring-cloud-gateway.jar"]