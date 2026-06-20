# Blogicum
Платформа для блогов. Позволяет вести свой блог и читать блоги других пользователей.
## Стек:
Python, Django
## Запуск отладочного сервера под windows:
В директории с проектом
1. Создайте и активируйте виртуальное окружение:
```commandline
python -m venv venv
```
2. Активируйте виртуальное окружение:
```commandline
source venv\Scripts\activate  
```
3. Установите зависимости:
```commandline
pip install -r requirements.txt
```
3. Выполните миграции:
```commandline
cd blogicum
python manage.py migrate
```
4. Запустите сервер:
```commandline
python manage.py runserver
```
Проект будет доступен по адресу: http://127.0.0.1:8000/