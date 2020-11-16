FROM openjdk:8-jre

RUN mkdir -p /app

COPY itoken-zipkin-1.0.0-SNAPSHOT.jar /app/

CMD java -jar  /app/itoken-zipkin-1.0.0-SNAPSHOT.jar --spring.profiles.active=prod

EXPOSE 9411
