###Microblog от автора Miguel Grinberg


![Книга](https://image.ebooks.com/cover/96034028.jpg)
запуск
режим продакшна
```bash
FLASK_APP=microblog.py
FLASK_DEBUG=0
flask run
```

Используемые пакеты в requirements.txt
```bash
pip install -r requirements.txt
```

Для теста отправки на email (ошибки сервиса - отправка письма админу, сообщения пользователям о паролях, сброс и пр.)
```bash
aiosmtpd -n -c aiosmtpd.handlers.Debugging -l localhost:8025
```
