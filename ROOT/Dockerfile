FROM tomcat:9.0-jdk17
ENV PORT=8080
RUN rm -rf /usr/local/tomcat/webapps/ROOT
COPY target/BloodBankApp.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
