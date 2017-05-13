## Hibernate ORM
Application in Wildfly JEE <br />
UI: JSF <br />
ORM: Hibernate 5 <br />
Database: H2 <br />



### Technologies
JSF, CDI, EJB, JPA, Hibernate



### Steps
###### Start a Wildfly Server:
For Linux:   *WILDFLY_HOME/bin/standalone.sh* <br />
For Windows: *WILDFLY_HOME\bin\standalone.bat*

###### Build and Deploy the Application:
*mvn clean install wildfly:deploy*

###### Access the Application:
http://localhost:8080/hibernate5

###### Undeploy Application:
*mvn wildfly:undeploy*


### original source
<https://github.com/wildfly/quickstart/>







