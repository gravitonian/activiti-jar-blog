# Activiti Extension Module for blog "Getting Started with Alfresco Activiti Enterprise"

See: https://docs.google.com/document/d/1ggrlWtSTxjvlbL0KzZSkZ6rmNu6wud5T4es8zeqTMyU/pub

To run use `mvn clean install alfresco:run` or `./run.sh` and verify that it 

 * Runs the embedded Tomcat + H2 DB 
 * Runs Activiti App
 * Packages both a JAR with customization and a ZIP with the whole Activiti App
  
# Few things to notice

 * No parent pom
 * WAR assembly is handled by the Alfresco Maven Plugin configuration
 * Standard JAR packaging and layout
 * Works seamlessly with Eclipse and IntelliJ IDEA
 * No unit testing/functional tests just yet
    
  
 
