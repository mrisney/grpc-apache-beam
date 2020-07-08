### grpc-apache-beam

### Simple GRPC Client Server
### Prerequisites
-------------
This project uses Maven for assembling a jar filebased on artifacts in Maven Central or
any other accessible Maven repository.

1. Install Java (JDK 8 preferred) and Maven.
2. Clone this repository and go into the repository root folder.
3.  `cd grpc-apache-beam`

###  How to build the GRPC Hello World Server 
---------------------------------
1. Clone this repository and go into the repository root folder.
2. Run the following command to build a jar file with all depencies
3.  `mvn clean install`
4.  This will build a 'FAT' jar with all dependecies. 

### Running the GRPC Server
to run the server.
```sh
$ cd grpc-apache-beam
$ java -jar target/grpc-beam-1.0-jar-with-dependencies.jar
```