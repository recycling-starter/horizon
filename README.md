# Recycling starter

## Task manager

+ ~~[Trello](https://trello.com/restarter/home)~~
+ [Asana](https://app.asana.com/0/home/1186317738561554)

## Design

+ [Ссылка на дизайн в Zeplin](https://zpl.io/VOO0ypX)
+ [Скачать Zeplin](https://zeplin.io/)

## API

### API представляет собой коллекцию запросов в Postman

+ [Ссылка на API](https://documenter.getpostman.com/view/10561517/T1DtfbkE?version=latest)
+ [Скачать Postman](https://www.postman.com/downloads/)

### Пример кода в Request Body:

```json
{
  "email": "email@domain.com",
  "password": "123456"
}
```

## Стиль именования коммитов

### Тип коммита

Каждый коммит начинается с указания типа. В нашем случае будет это:

+ feature — добавление новой функциональности
+ fix — исправление бага, влияющего на работу приложения
+ style — исправление всего, что касается внешнего вида
+ refactor — рефакторинг кода приложения
+ test — всё, что связано с тестированием
+ chore — обычное обслуживание кода (например, изменилось API и вы поменяли код под новое)

### Область действия

Сразу после типа коммита без всяких пробелов указываем в скобках область, на которую распространяется наш коммит.

Например, может быть область видимости модуля:

```console
refactor(operator) use common library for all controls
```

Или область видимости файла:

```console
chore(gruntfile.js) add watch task
```

### Текст коммита

Текст коммита должен удовлетворять следующим условиям:

+ В начале текста сказано, что вы сделали (например, add), далее – сущность (например, operator screen) и в конце – подробности (profile page)
+ Всё написано с маленькой буквы, при необходимости, используется kebab-case
+ Всё написано на английском языке 
+ Время всегда настоящее (не прошлое!)

### Пример коммита

```console
git commit -m "feature(operator) add operator screen profile page"
```

## Front-end

Размещён по адресу [https://re-starter.herokuapp.com](https://re-starter.herokuapp.com)

## Back-end

Размещён по адресу [https://oreldaniil.pythonanywhere.com](https://oreldaniil.pythonanywhere.com)
