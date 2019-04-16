FROM openjdk

VOLUME /tmp
ADD maven/QuoteMakerEureka-0.0.1-SNAPSHOT.jar quoteMakerEureka.jar
RUN sh -c 'touch /quoteMakerEureka.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/quoteMakerEureka.jar"]