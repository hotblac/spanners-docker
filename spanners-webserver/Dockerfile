FROM tomcat:7-jre8
MAINTAINER Stuart 'Stevie' Leitch <hotblack@disasterarea.org.uk>

# Copy modified context.xml to Tomcat/
ADD tomcat/context.xml $CATALINA_HOME/conf/
ADD tomcat/tomcat-users.xml $CATALINA_HOME/conf/
ADD tomcat/mysql-connector-java-5.1.36-bin.jar $CATALINA_HOME/lib/
