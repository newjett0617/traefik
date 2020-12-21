# traefik

```
docker network create reverse-proxy
```

```
docker-compose --file traefik.yml up -d
```

```
docker-compose --file whoami.yml up -d
```

```
curl -H 'Host: whoami.localhost' http://127.0.0.1:80
```
