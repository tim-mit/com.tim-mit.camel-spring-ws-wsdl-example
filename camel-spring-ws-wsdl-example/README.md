# camel-spring-ws-wsdl-example

This is an example Maven project which shows how to use Camel to route a request to a webservice defined in a WSDL via the camel-spring-ws artifact.

## Running

Build the project in Eclipse and run as a Java Application, it'll send two requests to the webservice and then wait.

## Debugging

The Maven pom.xml has a reference to the name of the project, this'll need to be updated to the name you have for any project that may have been copied from this one.

You may need to fiddle with the build configuration for the project. This is intended to run as a Java Application, search for the main class and use the Spring one that is one of those found.