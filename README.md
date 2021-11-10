# Spring Kafka Streams using Spring Cloud Streams End to End example

## Endpoint
- http://localhost:8080/domain/lookup/facebook - to pull all facebook related web domain names

## Microservices
- 'domain-crawler' - uses Spring Kafka
- 'domain-processor' - uses Spring Cloud Stream with Kafka Streams binder
- 'domain-service' - uses Spring Cloud Stream with Kafka Streams binder

## Architecture
![architecture](architecture.png)

## For DOCKER set up
Please refer to this 
```
https://docs.confluent.io/platform/current/quickstart/ce-docker-quickstart.html```
```

## Youtube link for this project -TechPrimer good explaination
https://www.youtube.com/watch?v=rqjdSbIOrJ4