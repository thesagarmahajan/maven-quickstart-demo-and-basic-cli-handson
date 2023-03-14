# Maven Installation

- Step-1  Visit https://maven.apache.org/download.cgi and download the .zip file.
- Step-2  Extract the zip file and place the extracted directory in the java folder
- Step-3  Add MAVEN_HOME Path to environment variable
- Step-4  Open cmdterminal and run ``` mvn --version ``` to verify the installation


# Maven Quickstart

- Creating Maven Quickstart project
```
mvn archetypegenerate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```

- Building the project
```
mvn package
```

- Test the newly compiled and packaged JAR
```
java -cp targetmy-app-1.0-SNAPSHOT.jar com.mycompany.app.App
```
