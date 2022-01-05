FROM openjdk:11
VOLUME /tmp
EXPOSE 8080
ADD ./target/dscatalog-0.0.1-SNAPSHOT.jar dscatalog-nelio.jar
ENTRYPOINT ["java","-jar","/dscatalog-nelio.jar"]