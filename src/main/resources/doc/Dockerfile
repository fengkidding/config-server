FROM java:8

MAINTAINER root

COPY config-server.jar /app.jar

ENV JAVA_OPTS="\
-server \
-Xmx300m \
-Xms300m "

EXPOSE 11000
ENTRYPOINT ["java","-jar","/app.jar"]