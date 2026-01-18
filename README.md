Kittygram — Instagram для котиков!
Создайте стильный профиль для вашего пушистого друга. Добавляйте фото, отмечайте породу и день рождения, делитесь забавными привычками и следите за другими усатыми звёздами. Вся кошачья жизнь в одном приложении!

Все мурлыкают здесь. Kittygram.
Храните моменты. Делитесь мурчанием.




Стек технологий для Kittygram
Backend
Python 3.9+ (совместимость с Django 3.2.3)
Django==3.2.3 — основной веб-фреймворк
Django REST Framework==3.12.4 — для построения REST API
Djoser==2.1.0 — аутентификация и управление пользователями
PostgreSQL 13+ — основная реляционная база данных
Psycopg2-binary==2.9.3 — драйвер PostgreSQL для Python
Pillow==9.0.0 — обработка изображений котиков
Webcolors==1.11.1 — работа с цветами

Frontend
JavaScript без тяжелых фреймворков
HTML5/CSS3 — верстка и стилизация

Инфраструктура и инструменты
Docker + Docker Compose — контейнеризация приложения
Gunicorn==20.1.0 — WSGI-сервер для продакшена
Nginx — веб-сервер и reverse proxy
GitHub Actions — пайплайны сборки и деплоя
Pytest==6.2.4 с pytest-django==4.4.0 — тестирование
PyYAML==6.0 — работа с YAML-файлами



Создайте файл .env в корне проекта:
DEBUG=False
SECRET_KEY=ваш секретный ключ
ALLOWED_HOSTS=localhost,127.0.0.1,backend,ваш-домен.ру

DB_NAME=название вашей бд
POSTGRES_USER=ник 
POSTGRES_PASSWORD=ваш пароль
DB_HOST=db
DB_PORT=порт для базы данных
