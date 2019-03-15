FROM openjdk:10-jre-slim
EXPOSE 9000
COPY target/*SNAPSHOT.jar /app/ 
WORKDIR /app
#CMD java -jar -Dvertx.disableFileCPResolving=true *SNAPSHOT.jar 
CMD java -jar -Dvertx.disableFileCPResolving=true *SNAPSHOT.jar --add-modules java.xml.bind
USER root
