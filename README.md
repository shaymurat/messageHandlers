# Домашнее задание по теме "Хендлеры обработки сообщений".

Цель: написать простейшего телеграм-бота, используя асинхронные функции.

Подготовка:

Выполните все действия представленные в предыдущих видео модуля, создав
и подготовив Telegram-бот для дальнейших заданий.
Нужные версии для 13 и 14 модулей и вашего виртуального окружения
находятся [здесь](https://drive.google.com/file/d/1gAp3ulJNLwnWjFXf5bL3LNC_vuF_890m/view?usp=sharing).
```
----requirements.txt-----
aiogram==2.25.1
aiohttp==3.8.6
aiosignal==1.3.1
async-timeout==4.0.3
attrs==23.2.0
Babel==2.9.1
certifi==2024.7.4
charset-normalizer==3.3.2
frozenlist==1.4.1
idna==3.7
magic-filter==1.0.12
multidict==6.0.5
pytz==2024.1
yarl==1.9.4
```

Если не помните, как установить необходимые
библиотеки, обратитесь к материалам 11 модуля.
Актуальная версия Python для дальнейшей работы -
[3.9.13](https://www.python.org/downloads/release/python-3913/).

## Задача "Бот поддержки (Начало)":

К коду из подготовительного видео напишите две асинхронные функции:
1. ```start(message)``` - печатает строку в консоли ```'Привет! Я бот
   помогающий твоему здоровью.'``` . Запускается только когда написана
   команда '```/start```' в чате с ботом. (используйте соответствующий
   декоратор)
2. ```all_massages(message)``` - печатает строку в консоли ```'Введите команду
   /start, чтобы начать общение.'```. Запускается при любом обращении не
   описанном ранее. (используйте соответствующий декоратор)

Запустите ваш Telegram-бот и проверьте его на работоспособность.

Пример результата выполнения программы:

Ввод в чат Telegram:
```
Хэй!
/start
```

Вывод в консоль:
```
Updates were skipped successfully.
Введите команду /start, чтобы начать общение.
Привет! Я бот помогающий твоему здоровью.
```

Примечания:
> 1. Для ответа на сообщение используйте декоратор ```message_handler```.
> 2. При отправке вашего кода на GitHub не забудьте убрать ключ для
     подключения к вашему боту!

Файл module_13_2.py загрузите на ваш GitHub репозиторий. В решении пришлите
ссылку на него.

Успехов!
