---
layout: page
title: INSTEAD Клуб
disqus: y
---
## Добро пожаловать!

Что это? Уютное место для тех, кто устал от публичности. Для тех, кто хочет
пообщаться в более неформальной обстановке. Это узел в сети [IDEC](https://github.com/idec-net/new-docs/blob/master/main.md).

Для общения, вы можете использовать веб интерфейс: [club.hugeping.ru](http://club.hugeping.ru)

А также, вы можете воспользоваться [caesium](https://github.com/idec-net/caesium) и читать/писать сообщения прямо из вашего Unix.

Эхи узла, которые посвящены INSTEAD:

- std.club - общение;
- std.game - игры INSTEAD;
- std.prog - программирование игр в INSTEAD;
- std.tech - технические вопросы INSTEAD;

## Правила разметки

Для цитирования используйте >:

```
> Это цитаты
> Цитирование

А это текст!
```

Для описания блоков кода, используйте ====:

```
====
dprint("hello world!")
====
```

Для спойлеров, используйте %%spoiler%%:

```
Это открытая часть сообщения.

@spoler: А это то, что попадет в спойлер base64
```

## Настройки цезия

Интерфейс цезия напомнинает GoldEd (для тех, кто в курсе).

```
nodename club
node http://club.hugeping.ru/

auth $AUTHSTR$
to $NAME$

echo std.club Клуб
echo std.game Игры
echo std.prog Программирование
echo std.tech Технологии
```

$AUTHSTR$ -- тут вы вводите ту строку, которую видите в authstr: по адресу: [http://club.hugeping.ru/profile](http://club.hugeping.ru/profile) (после
регистрации)

$NAME$ -- ваш ник при регистрации.


