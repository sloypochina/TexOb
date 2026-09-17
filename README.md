# Статический сервер Nginx в Docker

Репозиторий содержит лабораторную работу №1 по развертыванию веб-сервера Nginx.

## Инструкция по запуску

1. **Сборка Docker-образа:**
   ```bash
   docker build -t nginx-static-site .
   ```

2. **Запуск контейнера вручную:**
   ```bash
   docker run -d --name nginx-site -p 8080:80 --restart always nginx-static-site
   ```

