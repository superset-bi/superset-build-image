# superset-build-image
Как сбилдить образ суперсета с плагином из npmjs репозитория. Dockerfile для сборки образа для версии 3.1.2 и выше

Запускаем сборку образа командой:
```
sudo docker build -f Dockerfile_CH --force-rm -t clickhouse-superset:3.1.1 .
```