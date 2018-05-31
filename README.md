# MTProxy
My version docker-compose file for MTProxy server

create volume:
`docker volume create --name=proxy-config`

create key:
`openssl rand -hex 16`

start daemon:
```
cd mtproxy
docker-compose up -d
```
