 #KubeDemo
docker run -it --rm -p 8888:8080 -v /tmp/tomcat-users.xml:/usr/local/tomcat/conf/tomcat-users.xml:ro -v /tmp/webapps:/usr/local/tomcat/webapps:rw tomcat:7

