FROM java:8
VOLUME /tmp
ADD ./target/turbine-1.0.0-SNAPSHOT.jar /app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 8766
ENTRYPOINT ["java","-jar","/app.jar"]