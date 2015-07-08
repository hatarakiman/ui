# Header

Блок реализует отображение верхней части страницы с логотипом, меню и информацией о пользователе.

## Специализированные поля блока

Список зарезервированных полей входного BEMJSON:

<table>
    <tr>
        <th>Поле</th>
        <th>Тип</th>
        <th>Описание</th>
    </tr>
    <tr>
        <td>menu</td>
        <td>
            <code>Array</code>
        </td>
        <td>Массив объектов для построения меню</td>
    </tr>
</table>

## Модификаторы блока

### Модификатор `fixed`

#### Прилепленный к верху вьюпорта (модификатор `fixed` в значении `true`)

Блок всегда находится в верху вьюпорта.

## Элементы блока

### __inner

Обертка для нужд верстки.

### __menu

Реализует меню из входного массива объектов.

### __user

Реализует меню пользователя.

### __support

Показывает город и номера телефонов для обращения в службу поддержки.
