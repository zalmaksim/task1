# Вводная

Требуется получить понимание того, как производятся веб-продукты.  
Без этого понимания, их тестирование будет затруднительно, и связано с постоянно возникающими проблемами, в связи с отсутствуием фундаментального понимания их работы / производства.

Подготовка тестировщика, будет строится из выполнения ряда практических заданий.  
В этих практических заданиях, будет разрабатываться полноценное приложение.  
Этапы разработки приложения выглядят следующим образом:

1. Верстка приложения;
2. Понимание принципа работы клиент-серверных приложений и протокола HTTP;
3. Разработка серверного функционала;
4. Разработка unit-тестов статического приложения;
5. Разработка функциональных тестов статического приложения;
6. Разработка JS функционала;
7. Работа с системами сборки.

# Задание на верстку

## Задача

Требуется сверстать простое приложение.  
**Не требуется верстка "пиксель в пиксель".**

![Application](application.png)

## Информация

Информация для верстки.  
Ниже дана информация, которую нельзя/трудно вынести png макета.

- Шрифт: 'Helvetica Neue', Helvetica, Arial, sans-serif;
- Цвет: Вычисляется с помощью любого редактора/расширения браузера - [ссылка](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp);
- Отступы/размеры: Вычисляется с помощю расширения браузера - [ссылка](https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi);
- Тени можно сделать "на глаз";
- Галочка в поле для ввода, это повернутый utf символ `\u276F`;
- Символ крестика в ссылк на удаление таска, это utf символ `\u00D7`;
- Изображения о завершенном/открытом таске:  
  - `data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="-10 -18 100 135"><circle cx="50" cy="50" r="50" fill="none" stroke="#bddad5" stroke-width="3"/><path fill="#5dc2af" d="M72 25L42 71 27 56l-4 4 20 20 34-52z"/></svg>`;  
  - `data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="-10 -18 100 135"><circle cx="50" cy="50" r="50" fill="none" stroke="#ededed" stroke-width="3"/></svg>`.


### Требования

#### HTML
Необходимо использовать HTML5.  
Верстка должна быть семантичной - [ссылка1](http://html5book.org/semantics.html5), [ссылка2](https://vimeo.com/25823931).

HTML код необходимо разместить в файле `index.html` в корне проекта.

#### CSS
Основы верстки - [ссылка](http://softwaremaniacs.org/blog/category/primer/).

#### Структура файлов
Требуется использовать файловую структуру описаную у нас в wiki - [ссылка](http://wiki.webpp.ru/bitrixcs-ru.html#files).  
Поскольку сейчас разрабатывается только верстка, требуется использовать только папку `static`.

### Окружение
Рекомендуется при разработке верстки использовать тестовый сервер встроеный в PHP - [ссылка](http://php.net/manual/ru/features.commandline.webserver.php).

## Результат работы
Результат работы требуется запушить в репозиторий в отдельной ветке.  
Ветка должна называться так же, как логин пользователя в системе.

**Изменять `master` ветку - запрещено!**  

