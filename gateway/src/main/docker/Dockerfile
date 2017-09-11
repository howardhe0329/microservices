FROM java:8
MAINTAINER Howard He "hebin@jajaying.com"
VOLUME /tmp

ADD gateway-1.0.0.jar app.jar
RUN sh -c "touch app.jar"
EXPOSE 5555
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]