### Задача 2

На лекции мы рассматривали пример для военкомата. Сейчас мы знаем про его рост. Расширить это приложение следующими условиями:

1. Проверка на возраст призывника.
2. Количество детей.
3. Учится ли он сейчас.

### Решение
```python
height = int(input('Введите рост: '))
age = int(input('Введите возраст: '))
child = int(input('Количество детей: '))
study = input('Вы учитесь: ')


if 18 < age < 27 and child < 4 and study == "Нет":
    if height < 170:
        print('В танкисты')
    elif height < 185:
        print('На флот')
    elif height < 200:
        print('В десант')
    else:
        print('В другие войска')
else:
    print('Не годен')
```

### Задача 3

Разработать приложение для определения знака зодиака по дате рождения.
```
Пример:

Введите месяц: март
Введите число: 6

Вывод:
Рыбы
```

### Решение
```python
month = input('Введите месяц: ')
date = int(input('Введите число: '))

if month == 'январь':
  if date < 20:
    print('Козерог')
  else:
    print('Водолей')
if month == 'февраль':
  if date < 19:
    print('Водолей')
  else:
    print('Рыбы')
if month == 'март':
  if date < 20:
    print('Рыбы')
  else:
    print('Овен')
if month == 'апрель':
  if date < 19:
    print('Овен')
  else:
    print('Телец')
if month == 'май':
  if date < 20:
    print('Телец')
  else:
    print('Близнецы')
if month == 'июнь':
  if date < 20:
    print('Близнецы')
  else:
    print('Рак')
if month == 'июль':
  if date < 22:
    print('Рак')
  else:
    print('Лев')
if month == 'август':
  if date < 22:
    print('Лев')
  else:
    print('Дева')
if month == 'сентябрь':
  if date < 22:
    print('Дева')
  else:
    print('Весы')
if month == 'октябрь':
  if date < 22:
    print('Весы')
  else:
    print('Скорпион')
if month == 'ноябрь':
  if date < 21:
    print('Скорпион')
  else:
    print('Стрелец')
if month == 'декабрь':
  if date < 21:
    print('Стрелец')
  else:
    print('Козерог')
```
