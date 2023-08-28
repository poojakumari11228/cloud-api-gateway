# cloud-api-gateway
API Gateway - Microservices Architecture


# Part 1: Eureka cluster 

Write 2 Eureka services that work in a cluster of replicas. Give both the StockService and the ProductService the URL of both Eureka services. 

![image](https://github.com/poojakumari11228/cloud-api-gateway/assets/35136890/1ab89cb4-412f-4bdf-91f1-545d525571cb)


# Part 2: Load balancing with ribbon

Make 2 instances of the StockService, and make sure the 2nd stockservice runs at a different port.

![image](https://github.com/poojakumari11228/cloud-api-gateway/assets/35136890/348ffac7-ed21-4c3b-ae3c-6780a106e063)


# Part 3: API gateway

Write an API gateway in front of the ProductService and StockService so that the browser can call both services via the API gateway 

![image](https://github.com/poojakumari11228/cloud-api-gateway/assets/35136890/ff6be957-33d3-450d-abaf-b0ba1d53138b)
