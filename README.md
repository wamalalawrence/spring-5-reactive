## Real-time Event Streaming with Spring WebFlux 

### Technology Stack 
- Java 8 
- Mongo database 
- Maven 

### Build and run 
- mvn clean install 
- mongod 
- java -jar target/spring-5-reactive-0.0.1-SNAPSHOT.jar 

### Testing
At project build, tests will run and create one or two sample tweets, browse this url:  
http://localhost:8080/stream/tweets 
Tweets will be streamed to the browser and if you add more tweets, they will be streamed as you create them.