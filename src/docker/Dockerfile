FROM adoptopenjdk/openjdk8

VOLUME /tmp
ADD /spring-boot-mongodb-0.0.1-SNAPSHOT.jar spring-boot-mongo.jar
RUN sh -c 'touch spring-boot-mongo.jar'
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "spring-boot-mongo.jar"]
