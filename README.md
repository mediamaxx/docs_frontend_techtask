# Техническое задание на FrontEnd разработку

## Общие критерии к FrontEnd реализации

1. Приложенные дизайн-макеты
2. Требования к кроссбраузерности
3. Требования к наименованию классов
4. Закрытость к индексации
5. Поведение при переполнении блоков
6. Выравнивание блоков по высоте
7. Переполнение меню в header
8. Переполнение списка телефонов в header
9. Использование CSS-Grid
10. Стили контентных элементов (поддержка WISWYG)
11. Поддержка Fancybox 3
12. Корректное отображение изображений в контентных блоках
13. Каталожная сетка
14. Ссылки/кнопки
15. Телефонные номера
16. Маска телефонных номеров
17. Копирайт в футере
18. Правила работы слайдеров / каруселей
19. Запрет сборки js и css
20. Разметка форм под CF7
21. Псевдоэлементы используем только для декоративных элементов 
22. Не использовать комбинированное свойство background
23. Для стилизации элементов карт

## Комментарии по макетам

### Список уникальных макетов
1. Главная
2. Контентная страница
3. Контакты

#### Вводные по всем приведённым макетам

>**ВАЖНО**
>все контентные области должны поддерживать стилизацию элементов визуального редактора WYSWIG.

**Список областей:**

- https://i.imgur.com/NT689Zs.png
- https://i.imgur.com/NT689Zs.png 
- https://i.imgur.com/NT689Zs.png 

>Так же добавлять класс  clearfix для решения проблемы выпадения float-элементов

>У каждой секции должна быть отступы сверху-снизу, если они есть в макете. Причина - какая-то секция может не выводится, соответственно они не должны слипаться друг с другом.

Все ховеры реализовать согласно макету StyleGuide

### Ниже детализированные комментарии по макетам

1. Главная

2. Контентная

3. Контакты

### Адаптивное меню

Адаптивное меню реализовывается в точном соответствии с nic.ru 2 и 3 уровень вложенности выводятся сразу. 
2 уровень открывается панелью только пункты меню и перед ними ссылка на переход в родительский раздел http://prntscr.com/rae6ar - это единственное отличие! 
Т.е. если открыли панель с подразделами пункта “Домены” - сверху перед списком элементов - ссылка на страницу “Домены”
При этом в меню 1 уровня раздел “Домены” сам не кликабелен вместе со стрелкой - а только открываются следующую панель.

Реализовать пункты меню по дизайну 

1. Главная (Исп. дизайн-макет Главная)

2.	Услуги сантехника (Исп. дизайн-макет Услуга)
    1.	Аварийный выезд сантехника (Исп. дизайн-макет Услуга)
    2.	Устранение утечки (Исп. дизайн-макет Услуга)
    3.	Устранение засоров (Исп. дизайн-макет Услуга)
3. Контакты

`<html>`
`Демонстрация кода`
`</html>`

![Tux, the Linux mascot](/assets/images/tux.png)

