FROM jayavardhanpannem/springbootwithdocker-helloworld

MAINTAINER "Jayavardhan Pannem"

ENV JAVA_VERSION 8u31
ENV BUILD_VERSION b13

#EXPOSE 9000
#install Spring Boot artifact
VOLUME /tmp
ADD /maven/springbootwithdocker-helloworld.jar springbootwithdocker-helloworld.jar
RUN sh -c 'touch /springbootwithdocker-helloworld.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/springbootwithdocker-helloworld.jar"]


