
Here is a reference for commonly used Maven commands:

Basic Commands
Compile the project:
      
mvn compile
Package the project:
      
mvn package
Clean the project:
      
mvn clean
Install the project to the local repository:
      
mvn install
Deploy the project:
      
mvn deploy
Lifecycle Commands
Clean lifecycle (clean the project):
      
mvn clean
Default lifecycle (compile, test, package, etc.):
      
mvn default
Site lifecycle (generate project reports):
      
mvn site
Plugin Commands
Run a specific plugin goal:
      
mvn plugin:goal
For example, to use the compiler plugin to compile the project:
      
mvn compiler:compile
Project Management
Generate a new Maven project from an archetype:
      
mvn archetype:generate
Validate the project:
      
mvn validate
Test the project:
      
mvn test
Dependency Management
Show dependency tree:
      
mvn dependency:tree
Download sources and javadocs for dependencies:
      
mvn dependency:sources
mvn dependency:resolve -Dclassifier=javadoc
Running the Project
Run a Spring Boot application:
      
mvn spring-boot:run
Miscellaneous
Skip tests:
      
mvn install -DskipTests
Re-run failed tests:
      
mvn test -rf :module-name
Update the project:
      
mvn versions:use-latest-releases
