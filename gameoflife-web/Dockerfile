FROM tomcat

MAINTAINER localhost

RUN mv webapps webapps2 && mv webapps.dist/ webapps

COPY gameoflife.war /usr/local/tomcat/webapps/gameoflife.war

CMD ["catalina.sh" "run"]
