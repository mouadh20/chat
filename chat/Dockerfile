FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar chat.jar
ENTRYPOINT ["java","-jar","/chat.jar"]
EXPOSE 9090