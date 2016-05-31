# elk-stack

Running Elasticsearch + Kibana + Logstash stack with docker.

All images are official. You can find them in [Docker Hub](https://hub.docker.com/).


## Downloading Images:

```bash
docker pull elasticsearch:2.2.1
docker pull kibana:4.4.2
docker pull logstash:2.2.2
```

## Mounting and Running Images:

```bash
docker compose up -d
```


## Testing:

```
Open 127.0.0.1:5601 (Kibana Web UI)
```

```
echo Supertest! | nc 127.0.0.1 5555
```
