# datalens-proxy

Простой прокси-интерфейс для публичных дашбордов Yandex DataLens.  
Позволяет открывать дашборды по адресу:  
`http://datalens.price-solutions.ru/<HASH_ID>`

## Использование

```bash
docker network create shared  # (если еще не создана)
docker-compose up -d
