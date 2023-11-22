FROM tomcat:9-jre8-alpine
WORKDIR /usr/local/tomcat
COPY ./Docker/server.xml ./conf
RUN rm -rf ./webapps/*
COPY ./edu-msa-commnet/target/edu-msa-comment-1.0.0.war ./webapps/edu-msa-comment-1.0.0.war

EXPOSE 28083
