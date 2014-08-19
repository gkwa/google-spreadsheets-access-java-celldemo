google-spreadsheets-access-java-celldemo
========================================

```sh
mvn archetype:generate -DgroupId=com.streambox.celldemo -DartifactId=celldemo -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
# update pom to look like the one in this dir
mvn clean package; java -cp target/uber-celldemo-1.0-SNAPSHOT.jar com.streambox.celldemo.CellDemo --username username@gmail.com --password secret
```

Importing Maven based project into existing workspace
-----------------------------------------
Import project as Maven project into existing workspace using m2e connector.

1. Install m2e connector into eclipse (Eclipse Help, Install New Software, m2e connector)
2. right click Eclipse Package Explorer
3. Import
4. Maven Existing Projects
5. select project with pom.xml
