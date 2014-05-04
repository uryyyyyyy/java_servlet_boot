java_servlet_boot
=================


## setup

1. Local Java version should be 1.7 (javac --version)

1. execute [./gradlew eclipse] or [./gradlew.bat eclipse] -> create eclipse project

2. download tomcat7.X and extract (everywhere is OK)


## confirm

- in eclipse, [import] and [existing project]

- in Eclipse, check Referenced Libralies, h2 and junit should exist.

- in terminal(or cmd), execute tomcat7.X/bin/startup.sh(bat). and access to http://localhost:8080/ -> Tomcat TopPage are shown