FROM java:8

MAINTAINER Bousselmi Houssem Eddine bousselmi.houssem@gmail.com

VOLUME /tmp

ADD target/conference-app*.war app.war

RUN bash -c 'touch /app.war'

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.war"]
