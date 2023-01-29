
 ## Тестовое задание для компании **csort.ru**

REST API для ресурса User. В репозитории хранится openapi.json, документация к API

[![Rest api](https://i.imgur.com/Y9AvvDZ.jpg "Rest api")](https://i.imgur.com/Y9AvvDZ.jpg "Rest api")

Функционал. Ресурс пользователь
- Создание
- Удаление
- Получение всех пользователей
-Получение пользователя по идентификатору

### Инструкция по запуску
1. Клонировать репозиторий
```bash
git clone https://github.com/jycope/test-task-cstore.git
```
2. Перейти в директорию 
```bash
cd  test-task-cstore
```
3. Установить зависимости
```bash
 $ composer install
```
4. Указать логин и пароль от базы данных в` .env`
5. Провести миграции 
```bash
$ php artisan migrate
```
6. Запустить сервер
```bash
$ php artisan serve
```
