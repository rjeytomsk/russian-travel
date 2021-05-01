[Ссылка на сайт](https://github.com/rjeytomsk/russian-travel/index.html)

# Путешествия по России

Лендинг о красивых местах нашей необъятной, в которых стоит побывать каждому.

## Описание
На сайте применяются каскадные таблицы стилей ([CSS](https://www.w3.org/Style/CSS/Overview.en.html)). Используется методология [БЭМ](https://ru.bem.info/methodology/) и схема организации файловой структуры [Nested](https://ru.bem.info/methodology/filestructure/#nested). Соблюдена правильная [HTML-семантика](https://www.w3schools.com/html/html5_semantic_elements.asp), а также ипользуется вёрстка для правильного отображения сайта на [разных устройствах](https://screensizemap.com/). Для верстки макета использовалась [Figma](https://www.figma.com/) (выгрузка изображений производилась там же). Для "ужимания" png-шек был задействован сайт [tinypng.com](https://tinypng.com/)

## Установка

Разместите родительский каталог на собственном или стороннем веб-сервере.

## Описание основных стилей и страниц

Название файла, папки | Содержание файла, папки
----------------------|---------------------------------------------------------
normalize.css         | Нормалайзер CSS от Яндекс.Практикум
page.css              | Описывает основной блок сайта
content.css           | Описывает блок для контента внутри страницы
header                | Стили для шапки
footer                | Стили для подвала сайта
index.html            | Файл для отображения сайта в браузере

## Разработан с помощью инструментов

* [HTML](https://html.com/)
* [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
* [Figma](https://www.figma.com/)
* [tinypng.com](https://tinypng.com/)
* [VS Code](https://code.visualstudio.com/)
* [GitHub](https://github.com/)
* [Git Bash](https://git-scm.com/downloads)
* [Google Chrome](https://www.google.com/intl/ru_ru/chrome/)

## Проверка

Перед выгрузкой проведена проверка файлов стилей и страниц с помощью валидаторов от w3.org: [CSS-validator](https://jigsaw.w3.org/css-validator/) и [HTML-validator](https://validator.w3.org/).

## Пример анимации на сайте
**Затемнение блока при наведении**
![Затемнение блока при наведении](https://github.com/rjeytomsk/russian-travel/blob/main/images/readme/hover-cover.gif)

## Пример кода медиа-запроса для отзывчивой вёрстки

```css
@media screen and (max-width: 1279px) {
  .page__container {
    padding: 28px 0 24px 0;
  }

  .header {
    max-width: calc(100% - 96px);
  }
```

## Доработка проекта
Требуется исправить все будущие замечания от ревьюера ;)

## Автор

**Евгений Романовский** - [rjeytomsk](https://github.com/rjeytomsk)

## Благодарности за помощь

* **Яндекс.Практикум** за подробный бриф первого проекта
* **Сергею Константинову**, наставнику группы **lightcoral** 26го потока курса "Веб-разработчик" от **Яндекс.Практикум**
* Старшему студенту **Андрею Зайцеву**
* Всем учащимся группы **lightcoral**
* Кажому ревьюру **Яндекс.Практикум** в отдельности

#### 2021
#### Яндекс.Практикум
