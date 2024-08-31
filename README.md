
启动 traefik 容器
```sh
$ docker-compose --project-name=traefik --file docker-compose.traefik.yml up --detach
```
启动 web 容器

```sh
$ docker-compose --project-name=traefik  up --detach
```


访问 localhost:8080 进入 traefik 管理界面。 localhost 访问 web 容器的服务。