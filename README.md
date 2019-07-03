# logstash-on-docker

## Requirement
- docker
- docker swarm
- docker-compose

## How to Use
### Create
`docker stack deploy --compose-file docker-compose.yml  "stack-name"`

### List Service
`docker service ls`

### Inspect container log
`docker service logs -f "service-name"`

### Remove
`docker stack rm "stack-name"`
