### Run project
`./scripts/start.sh`

### Get Gateway of docker container
`docker inspect -f '{{range.NetworkSettings.Networks}}{{.Gateway}}{{end}}' <container_name_or_id>`

172.18.0.1


### Get IP address of docker container
`docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' <container_name_or_id>`

172.18.0.2


