# Maven wrapper task

I was supposed to add maven wrapper to this project to pass successfully. All
I had to do was to run the following command on the root of the project: 

`mvn -N io.takari:maven:wrapper`

This command created three new files in the root of the project: 

| file     | type           |
|----------|----------------|
| .mvn     | directory file | 
| mvnw     | batch file     |
| mvnw.cmd | cmd file       |

The purpose behind this was to make our application portable, it means, maven
wrapper allows other machines to work with the project without having maven
installed even, only JDK is mandatory.
