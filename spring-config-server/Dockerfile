FROM openjdk:8
ADD  /target/spring-config-server-0.0.1-SNAPSHOT.jar spring-config-server.jar
RUN git config --global http.sslVerify false
EXPOSE  9000
ENTRYPOINT  ["java","-jar","spring-config-server.jar"]

