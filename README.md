#Maven Matlab Simple Archetype

maven-archetype-matlab-simple is an archetype which contains a sample Maven project for matlab application.

	project
	|-- pom.xml
	`-- src
		|-- assembly
		|	`-- bin.xml (Packaging instructions)
	    |-- main
	    |   `-- matlab
	    |		`-- +sample
	    |       	`-- App.m (Source code)
	    `-- test
	        `-- matlab
	            `-- AppTest.m (Test code)

## Usage

```
mvn archetype:generate -DgroupId=com.github.ragavsathish -DartifactId=my-app \
-DarchetypeGroupId=com.github.ragavsathish \
-DarchetypeArtifactId=matlab-simple-archetype \
-DarchetypeVersion=1.0-SNAPSHOT \
-DinteractiveMode=false

```
