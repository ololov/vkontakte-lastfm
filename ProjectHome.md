Приложение для показа статистике last.fm на базе ВКонтакте API. Приложение построено на базе ActionScript-3 библиотеки http://code.google.com/p/vkontakte-as3/

Адрес приложения для добавления на свою страницу:
http://vkontakte.ru/apps.php?act=s&id=67225

## Порядок сборки ##

Для сборки нужен [Flex Builder 3](http://www.adobe.com/products/flex/) и SVN-client (например, http://tortoisesvn.tigris.org/).

1. Скачать исходные коды из SVN, как описано на http://code.google.com/p/vkontakte-lastfm/source/checkout

2. Проимпортить проект в Flex Builder (File/Import...)

3. Зарегистрировать на себя ВКонтакте пустое приложение

4. Поменять в index.template.html: viewer\_id, user\_id и api\_id на свои собственные (note: в двух местах)

5. Прописать в lastfm.mxml: API\_ID, API\_SECRET и DEBUG\_MODE.

6. Собираем, дебажим, поправляем, запускаем из Flex Builder-а

_Знакомые собирали нечто подобное на Flex SDK, но там все помуторнее будет, чтобы это описывать, кто пользуется - сам разберется. Все похоже, главное отличие, что билдить надо lastfm.mxml как главный файл проекта, ну и самому написать тестовую HTML для запуска, чтобы правильные FlashVars передавались._

## Предложения и пожелания ##

Все предложения и пожелания отправляйте администратору проекта по адресу [nn.knows@gmail.com](mailto:nn.knows@gmail.com) или [добавьте новый запрос](http://code.google.com/p/vkontakte-lastfm/issues/entry)