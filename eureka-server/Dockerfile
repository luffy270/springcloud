FROM java:8-alpine
VOLUME /tmp
ADD target/eureka-server-0.0.1-SNAPSHOT.jar app.jar
RUN sh -c  'touch /app.jar'
EXPOSE 1111 
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]

