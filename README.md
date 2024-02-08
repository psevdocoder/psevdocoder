## 💻 Tech Stack
![Golang](https://img.shields.io/badge/go-%2300ADD8.svg?style=flat&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) [![Gin - Golang](https://img.shields.io/badge/Gin-Golang-blue?logo=gin&logoColor=red)](https://gin-gonic.com/) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=flat&logo=django&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=flat&logo=nginx&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=flat&logo=sqlite&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)
## 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=psevdocoder&theme=radical&hide_border=false&include_all_commits=false&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=psevdocoder&theme=radical&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=psevdocoder&theme=radical&hide_border=false&include_all_commits=false&count_private=true&layout=compact)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

- 🔭 I’m currently working on [GroupAssist](https://github.com/psevdocoder/GroupAssist)
- 🌱 I’m currently learning **Golang** with backend frameworks

## Основные проекты
### 1. [Group Assistant](https://github.com/psevdocoder/sipi_backend)
Бекенд приложение на архитектуре RESTful API для автоматизации создания очередей для сдачи работ, фиксирования посещаемости студентов, создания опросов внутри группы. Написано на Python + Django REST Framework. Разделение функционала на основе пользоватеских ролей. Авторизация и аутентификация при помощи JWT токенов. Автоматизация развертывания реализована с использованием CI/CD workflows в связке с Docker и Nginx.

Swagger-документация к API: https://assistant.5pwjust.ru/api/swagger/

### 2. [TimeBotGolang](https://github.com/psevdocoder/timeBotGolang)
Телеграм бот, написанный на Go + [Telebot](https://github.com/tucnak/telebot) делающий парсинг сайта в массив времен на текущую дату и отправляющий заранее уведомления пользователям из белого списка при помощи [gocron](https://github.com/go-co-op/gocron).
Через замыкания с Middleware реализовано разделения пользователей на три категории: пользователи из белого списка (доступен базовый функционал), администратор (доступно частичное изменение конфигурации бота), игнорируемые пользователи - те, кто случайно могут найти бота, но будут им проигнорированы.

### 3. [Group Assistant (Rewritten on Go)](https://github.com/psevdocoder/GroupAssist)
In progress.

Имлементация-переосмысление первого проекта на языке Go. Написание кода с внедрением чистой архитектуры проекта для обеспечения фреймворконезависимости и облегчения расширяемости приложения. Используется библиотека [SQLX](https://github.com/jmoiron/sqlx) на уровне репозиториев, фреймворк [Gin](https://github.com/gin-gonic/gin) на уровне Transport/REST для обработки http запросов. Реализован слой бизнес-логики приложения, использующий DTO для манипуляций. Внедрена [swagger-документация](https://github.com/swaggo/swag). 
