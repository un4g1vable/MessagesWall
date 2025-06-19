# 💬 Стена сообщений
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-E74430?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005E87?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=xampp&logoColor=white)
![Composer](https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

CRUD-приложение, позовляющее создавать пользователей и писать сообщения на стену от их лица

## 🌟 Функциональные возможности
- Авторизация с помощью сессий
- Работа с базой данных
- Создание и редактирование собственных постов
- Просмотр всех постов от лица гостя

## 🛠 Установка и запуск
```bash
# Клонирование репозитория
git clone https://github.com/un4g1vable/MessagesWall.git

# Копирование файлов в папку Xampp
C:\xampp\htdocs\MessagesWall

# Установка PHP-зависимостей
composer install

# Настройка окружения
cp .env.example .env


APP_URL=http://localhost/PHPProject/public

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=phpproject_db
DB_USERNAME=root
DB_PASSWORD=

# Создание БД
'''
Откройте http://localhost/phpmyadmin
Создайте новую базу данных с именем phpproject_db
Используйте кодировку utf8mb4_general_ci
'''

# Генерация ключа приложения и миграции
php artisan key:generate
php artisan config:clear
php artisan migrate

# Установка фронтенд-зависимостей и сборка
npm install
npm run build

# Запуск проекта
http://localhost/PHPProject/public/login


```
