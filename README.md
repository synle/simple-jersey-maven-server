simple-jersey-maven
==================


Source: https://jersey.java.net/documentation/latest/getting-started.html




To Install and Run
```
mvn clean:install
mvn exec:java 
```


To Test
```
curl http://localhost:8080/myapp/myresource
```


Generate Brandnew project from Archetype
```
mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-grizzly2 \
  -DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false \
  -DgroupId=com.example -DartifactId=simple-service -Dpackage=com.example \
  -DarchetypeVersion=2.25.1
```
