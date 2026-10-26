# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a

## Лабораторная работа 2 — работа с Git

Библиотека содержит модули `circle.py` и `square.py` для вычисления площади
и периметра круга и квадрата. Требуется Python 3; сторонние пакеты не нужны.
Команды выполняются из корня репозитория.

```python
import circle
import square

# Радиус круга и сторона квадрата заданы в одинаковых единицах длины.
radius = 3
side = 4

# Площадь измеряется в квадратных единицах, периметр — в единицах длины.
print("Площадь круга:", circle.area(radius))
print("Длина окружности:", circle.perimeter(radius))
print("Площадь квадрата:", square.area(side))
print("Периметр квадрата:", square.perimeter(side))
```

Проверка примера из командной строки:

```bash
python -c "import circle, square; print(circle.area(3), circle.perimeter(3)); print(square.area(4), square.perimeter(4))"
```

Для квадрата со стороной 4 результат: площадь 16, периметр 16.
Для круга радиуса 3 результат приблизительно: площадь 28.27433,
длина окружности 18.84956.

Этот коммит изменяет только документацию в `docs/README.md`.
