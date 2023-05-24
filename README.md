# Cassandra 3 nodes cluster

To deploy Cassandra's cluster on **the same docker host** use the following command:
```
docker-compose up -d
```

To deploy Cassandra's cluster on **separate docker hosts** use deployment with Docker Swarm mode:
```
docker stack deploy --compose-file docker-compose.yml cass_3x_cluster
```
