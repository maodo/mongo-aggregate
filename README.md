# mongo-aggregate
Exemple d'utilisation de l'aggregation framework MongoDB en JAVA

#Cloning the project
git clone https://github.com/maodo/mongo-aggregate.git

#Importing the json to NoSQL MongoDB
C:\mongo-aggregate>mongoimport --db stats  --collection accidents --file accidentologie.json --jsonArray


2016-11-03T11:16:19.455+0000    connected to: localhost



2016-11-03T11:16:21.723+0000    imported 13630 documents



#Build 
mvn clean install

#Running
mvn exec:java
