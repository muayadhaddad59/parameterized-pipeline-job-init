# Springboot Hello World App
This repository is used for Jenkins Training Demo

### Build JAR
```
mvn clean package -DskipTests=true
```

### Unit Test Cases
```
mvn test
```
- Total 6 test cases, out of which
  - All `6` test cases will pass and 
  - `No` failures!
 
### Deploy/Run
```
java -jar target/hello-demo-*.jar 
```

### Integration Testing (Return 200 OK response)
```
curl -s http://localhost:6767/hello"
```
# parameterized-pipeline-job-init
