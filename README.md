1. git clone https://github.com/jkeevk/docker_compose/tree/main

2. В корне проекта создайте файл .env (если его нет). В этом файле нужно указать параметры для подключения к базе данных:

SECRET_KEY=your_key
DEBUG=True
DATABASE_ENGINE=django.db.backends.postgresql
DATABASE_NAME=netology_stocks_products
DATABASE_HOST=postgres
DATABASE_PORT=5432
DATABASE_USER=your_user
DATABASE_PASSWORD=your_password

3. docker-compose up -d --build