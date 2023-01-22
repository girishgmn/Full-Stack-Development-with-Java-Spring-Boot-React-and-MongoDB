# Full-Stack-Development-with-Java-Spring-Boot-React-and-MongoDB

Backend API using Java spring boot and MongoDB

2 software downloads 

##JDK setup##

1. Java Development Kit JDK 17.0.6 

Thank you for downloading this release of the Java™ Platform, Standard Edition Development Kit (JDK™).

The JDK is a development environment for building applications and components 
using the Java programming language.

javac 17.0.6 c-compiler

2. code editor IDE --> for JAVA --> Intelligent IDEA


####MongoDB server creation####


MongoDB Atlas --> platform that allows spin up MongoDB servers on the cloud.

Login to MONGODB Atlas --> Create ORGANIZATION

New Project Creation:
--> create project 
--> add members if any 
--> Inside project now create a DB (shared)  
--> select Cloud Provider (AWS)

To access data stored in Atlas, you’ll need to 
--> create users and (DB access)
--> set up network security controls.(Network access)  [0.0.0.0/0]

Your first user will have permission to read and write any data in your project.
Username:SolidBull
Password:AKKMvxUHM3fiHgPT 

Now you can see DB up and running on MongoDB atlas.

we can use DB client to connect DB called mongodb compass

In MongoDB Compass --> new connection (Give Name) --> copy ENDPOINT from Mongodb atlas and paste here

2 default DB -> admin and Local
create New DB (+) --> DB name --> Collection name

collection name --> means tables inside DB [RDS] --> SQL
collection name --> Means movies(documents) inside DB [NRDS] --> NoSQL
