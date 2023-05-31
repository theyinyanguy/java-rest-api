# Sample Java REST API

## Use the following build config when creating this component in Choreo:

- Dockerfile: `java-rest-api/rest-api/Dockerfile`
- Docker context: `java-reat-api/rest-api/`
- Port: `8080` 
- OpenAPI filepath: `java-rest-api/rest-api/openapi.yaml`


## Use the following command to build and run the application locally.

> NOTE: You need to have java 17 installed in your system or a docker and VS Code installed to 
> open this in a dev container

Use following command to build the project
```bash
$ ./mvnw clean install
```

Run the service
```bash
$ ./mvnw spring-boot:run
```
