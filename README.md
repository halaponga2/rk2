### HTML

1. + HTML валиден, нет нарушений вложенности тегов.
1. + Есть заголовки первого уровня.
1. + Нет пропусков заголовков.
1. + Использованы семантические теги html5.
1. + Задан правильный язык страницы.
1. + Наличие мета-тега viewport.
1. + Верстка не "ломается" и данные читаются корректно при изменении размера (объема) контента (в частности, если у одного из элементов карточки отсутствует или, наоборот, слишком длинный текст)
1. + svg-иконки не засоряют основной код страницы (symbol, use).

### CSS

1. Изменено оформление у элементов формы.
1. +  Подключен и использован шрифт с Google Fonts.
1. + Изменяется оформление элемента при наведении на него курсора.
1. + Добавлен переход (transition).
1. + Добавлена анимация (средствами CSS).
1. + Элементы страницы хорошо читаемы.
1. ? Независимость блоков в CSS. При наведении на любой блок, в его стилях не должно быть множество перечёркнутых правил (следствие длинного каскада).
1. + Страницы отзывчивы (RWD). Адекватно отображаются при ширине экрана от 320px до 2560px:
1. + На малых экранах нет горизонтальной прокрутки. Все выстроену в одну колонку.
1. + На больших экранах страница ограничена по ширине, выравнивание по центру страницы должно быть сделано с помощью свойства margin. И примеры или подборки размещены в три колонки.
1. + Использована методология БЭМ при именовании классов. Если используется другая методология, она должна быть указана в комментариях в CSS.
1. Есть темная и светлая темы.
1. + SASS/SCSS.

### JavaScript

1. Реализован функционал списка:
1. Добавление нового элемента списка по нажатию на кнопку "добавить" или "+".
1. При добавлении нового элемента поля сбрасываются.
1. Удаление элемента списка с помощью кнопки в этом элементе списка.
1. Элемент списка можно отметить, как выполненный.
1. Отсутствуют ошибки в консоли браузера при работе пользователем со списком.
1. Реализована смена темы на странице.
1. Использован Vue.

### Дополнительно

1. + История в системе контроля версий (коммиты).
1. Использованы ветки в системе контроля версий.
1. + Страница проходит HTML и CSS валидацию.
1. + Код должен быть отформатирован (легко читаем).
1. + Проект структурирован. Файлы проекта распределены по папкам и не лежат все в корне.
1.  Страница удовлетворяет основным критериям доступности:
1.  Изменяемый размер шрифта (rem, em, %)
1. + Достаточный контраст
1. + alt у изображений
1. lable у всех интерактивных элементов
1. + адекватный tabindex
