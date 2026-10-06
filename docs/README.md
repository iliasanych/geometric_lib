# Документация проекта geometric_lib

## Общее описание решения

Библиотека `geometric_lib` содержит функции для вычисления площади и периметра геометрических фигур: круга и квадрата.

## Описание функций

### circle.py

#### area(r)
Вычисляет площадь круга по радиусу.

**Параметры:**
- `r` (float): радиус круга

**Возвращаемое значение:**
- `float`: площадь круга

**Пример вызова:**
```python
from circle import area
result = area(5)
print(result)  # 78.54
```


#### perimeter(r)
Вычисляет периметр (длину окружности) по радиусу.

**Параметры:**
- `r` (float): радиус круга

**Возвращаемое значение:**
- `float`: периметр круга

**Пример вызова:**
```python
from circle import perimeter
result = perimeter(5)
print(result)  # 31.42
```


### square.py

#### area(a)
Вычисляет площадь квадрата по стороне.

**Параметры:**
- `a` (float): длина стороны квадрата

**Возвращаемое значение:**
- `float`: площадь квадрата

**Пример вызова:**
```python
from square import area
result = area(4)
print(result)  # 16
```


#### perimeter(a)
Вычисляет периметр квадрата по длине его стороны.

**Параметры:**
- `a` (float или int): длина стороны квадрата

**Возвращаемое значение:**
- `float` или `int`: периметр квадрата

**Формула:**
P = 4 × a

**Пример вызова:**
```python
from square import perimeter
result = perimeter(5)
print(result)  # 20
```



## История изменений проекта

## История изменений проекта

## История изменений проекта

| Хеш коммита | Описание изменений |
| --- | --- |
| 8ba9aeb | L-03: Circle and square added |
| d078c8d | L-03: Docs added |
| 7bbff45 | Added docstring to circle.py functions |
| 6e762ee | Added docstring to square.py functions |
| 2ae0854 | Update of docs/README.md |
| 60bf56e | Добавлен README.md в корне репозитория |
| нет хэша | Update of history table |