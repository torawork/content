🛠 На одном домене несколько серверов могут обрабатывать каждый своё: кто-то электронную почту, кто-то файлы, кто-то сайт. Поэтому можно встретить URL с доменом третьего уровня, для почты ссылка с ним выглядит так:

```url
mail.google.com
```

А для сайта так:

```url
www.doka.guide
```

`www` расшифровывается как «World Wide Web», но сегодня уже не обязательно добавлять `www` к доменному имени, так как для большинства адресов настроен редирект на `www` версию или наоборот c `www` версии на обычную.

🛠 В JS есть удобный объект [`URLSearchParams`](/tools/urlsearchparams/) для создания поисковых ссылок. С его помощью можно настраивать и удобно вставлять в HTML пары ключ-значение для нужного запроса.

🛠 Быстро создать ссылку можно с помощью конструктора `URL()`, например:

```js
let url = new URL('https://doka.guide')
```
