# Java 11 runtime with AMD64 + ARM64 support
FROM eclipse-temurin:17-jre

ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
