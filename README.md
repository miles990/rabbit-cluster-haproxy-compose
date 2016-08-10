# RabbitMQ Cluster with Haproxy 

### Required
- [Docker Engine](https://docs.docker.com/engine/installation/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Run

```
git clone https://github.com/miles990/rabbit-cluster-haproxy-compose.git cluster
cd cluster
docker-compose up -d
```

### View Haproxy Statistics Report Web
[http://127.0.0.1:20000](http://127.0.0.1:20000)

### View RabbitMQ Management Web
[http://127.0.0.1:15672](http://127.0.0.1:15672)
