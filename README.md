REST test
==================

Создать БД 

В файле .env отредактировать подключение к БД

Выполнить **composer install**

Выполнить **php bin\console doctrine:migrations:migrate**

Выполнить **php bin/console audit:schema:update --force**

Запуск сервера **php bin/console server:run**
URL
http://127.0.0.1:8000/api