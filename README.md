# spring-cloud-config-server
Spring cloud config server to provide the configuration details for all microservices

# Below all microservice are comunicating with this config server to get the configuration details
1. countries-service
2. employee-service
3. zuul-service
4. eureka-server

# All endpoints
Eureka Server: http://localhost:8083/

Employee Service: http://localhost:8082/emp/employee-data

Countries Service: http://localhost:8081/countries/countries-list

Countries Service calling from Zuul GateWay API : http://localhost:8084/api/client/countries/countries-list

Employee Service calling from Zuul GateWay API : http://localhost:8084/api/server/emp/employee-data
