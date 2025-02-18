# Grupo Codar

## Objetivo

O objetivo desse repositório é criar exemplos de código para estudo de SOLID

## Ambiente

Para rodar o ambiente você precisa ter o docker e docker-compose instalados.

```bash
git clone git@github.com:marcelofabianov/dojo-codar-solid.git
```

```bash
cd dojo-codar-solid
```

```bash
docker compose up -d
```

```bash
docker exec -it app bash
```

```bash
composer install
```

### Rodando os testes

```bash
./vendor/bin/phpunit tests
```

ou 

```bash
composer test
```
