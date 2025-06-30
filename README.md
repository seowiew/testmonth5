rest api проект для блога

запуск:

без докера:
клонировать этот репозиторий + python manage.py runserver
с докером;
клонировать + docker-compose up --build
будет доступен на http://localhost:8000/api/v1/.../

аутентификация:
пароль и логин/токен

через токен:
получить через http://localhost:8000/api/token/ с json;
{
  "username": "*логин*",
  "password": "*пароль*"
}

через логин:
просто нажать log in и ввести логин и пароль




извините за то что нет swagger'а :-(
