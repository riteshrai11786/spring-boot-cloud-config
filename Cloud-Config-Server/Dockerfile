FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} cloud-gateway.jar
ENTRYPOINT ["java","-jar","cloud-config-server.jar"]
EXPOSE 9296