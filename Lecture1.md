## Архитектура веб-приложений
__TODO__

## REST

### Материалы

* __[!]__ Статья на википедии ([rus](https://ru.wikipedia.org/wiki/REST), [eng](https://en.wikipedia.org/wiki/Representational_state_transfer))
* [RESTful API Designing guidelines — The best practices](https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9)
* [10 Best Practices for Better RESTful API](10 Best Practices for Better RESTful API)
* __[adv]__ [The REST And Then Some](https://www.youtube.com/watch?v=QIv9YR1bMwY&list=PLd2MPdlXKO13USiCIT2tZ5IjIeZRFWHU0). Доклад про REST в целом.
* __[adv]__ [Versioning strategy for a complex internal API](https://www.youtube.com/watch?v=M2KCu0Oq3JE&index=2&list=PLd2MPdlXKO13USiCIT2tZ5IjIeZRFWHU0). Доклад про версионирование сложного API, используемого разными клиентами с разными функциональными возможностями от разработчика из Badoo. Не REST, но идеи, кажется, легко переносятся.

### Что нужно знать к экзамену
* Что такое REST, как он связан с HTTP
* 6 ограничений (constraints)
* Какова семантика HTTP методов и кодов ответа
* Какие существуют ожидания относительно URI ресурсов

## HTTP кеширование

### Материалы
* __[!]__ [HTTP caching on MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching)
* __[!]__ [Cache-Control on MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Cache-Control)
* HTTP Caching on Google Developers. [rus](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching?hl=ru) [eng](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

### Что нужно знать к экзамену
* Как Cache-Control влияет на кеширование, какие могут быть значения у заголовка.
* Как происходит кеширование при помощи даты модификации, какие заголовки участвуют.
* Как происходит кеширование при помощи etag, какие заголовки участвуют.
