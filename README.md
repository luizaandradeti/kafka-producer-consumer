"# Sample-Spring-Broker" 

https://spring.io/projects/

https://www.confluent.io/

https://www.confluent.io/learn/spring-boot-kafka/

https://spring.io/projects/

https://www.confluent.io/


````bash
docker-compose up -d
time="2025-05-07T16:23:05-03:00" level=warning msg="C:\\DEV\\producer\\spring\\docker-compose.yml: the attribute `version` is obsolete, it will be ignored, please remove it to avoid potential confusion"
[+] Running 3/3
✔ Network spring_broker-network  Created                                                                          0.0s
✔ Container zookeeper            Started                                                                          0.7s
✔ Container kafka                Started                                                                          0.7s
````


![Texto Alternativo](imgs/0.libs.png)
![Texto Alternativo](imgs1/applications.png)
![Texto Alternativo](imgs/2producer.png)
![Texto Alternativo](imgs/3envio.png)


````bash
curl --location 'http://localhost:4000/api/v1/msgs?key=1' \
--header 'Content-Type: text/plain' \
--data 'Hey, welcome!'
````



> [!NOTE]
>
> Repositorio com fins de estudos em contexto técnicos, estritamente na área de engenharia de software.
> Estudo não concluido#   k a f k a - p r o d u c e r - c o n s u m e r 
 
 
