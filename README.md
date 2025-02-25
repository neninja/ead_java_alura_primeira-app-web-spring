# ead_java_alura_primeira-app-web-spring

## Ambiente de desenvolvimento com Docker

- Suba o ambiente

```sh
docker-compose up -d
```

> Caso precise executar operações dentro do container, utilize `docker-compose exec app <comando>` ou acesse de maneira interativa usando `docker-compose exec app bash`

- Inicie o servidor de aplicação

```sh
docker-compose exec app mvn spring-boot:run
```

- Acesse `localhost:8080`
