Книжный интернет-магазин на API Google Books

В рамках проекта вам необходимо:

1) Сверстать главную страницу интернет-магазина Bookshop. Макет находится здесь.
2) Подключить Google Books API так, чтобы данные о книгах подгружались с сервера.
3) Подключить созданный вами ранее слайдер.
4) Поработать над правильной организацией проекта:
 4.1. реализовать модульную структуру;
 4.2. подключить Webpack;
 4.3. настроить сборку с минификацией.
5) Применить пройденные вами ранее инструменты оптимизации.

## Подготовка проекта
Для работы проекта необходим ключ от google API. Ключ нужно добавить в настройки проекта в файл ```src/settings.ts``` в параметр ```BOOKS_API_KEY```.
Без этого параметра компонент с книгами работать не будет.

## Сборка проекта
Установить зависимости:
```bash
npm i
```
Скомпилировать js и scss:
```bash
npm run build
```
Все что нужно для размещения на сервере после данного шага находится в папке ```dist```.

## Запуск dev-сервера
```bash
npm run start
```
