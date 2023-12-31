[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/pctDUmSd)
# Правила и регламент

- [Экзамен: правила, рекомендации и порядок проведения](https://hexly.notion.site/d9289c18871c44508bc7c7f05a51d94f)

## 1 задача

Напишите и экспортируйте функцию `multiplyTwoNumbers()`, которая возвращает множитель двух чисел.

**Параметры**

- *a*: первое целое число для умножения.
- *b*: второе целое число для умножения.

**Пример использования:**

```javascript
multiplyTwoNumbers(2, 3); // 6
multiplyTwoNumbers(-1, 3); // -3
multiplyTwoNumbers(150, 15); // 10
```

## 2 задача

Напишите и экспортируйте функцию `getMaxNumber()`, которая возвращает наибольшее число из двух аргументов.

**Параметры**

**Пример использования:**

- *a*: первое целое число для сравнения.
- *b*: второе целое число для сравнения.

```javascript
getMaxNumber(2, 12); // 12
getMaxNumber(40, 85); // 85
getMaxNumber(-155, 154); // 154
```

## 3 задача

Напишите и экспортируйте функцию `castReversedBoolean()`, которая возвращает инвертированное булево значение, основанное на переданном аргументе.

**Параметры**

- *value*: значение, которое требуется преобразовать.

**Пример использования:**

```javascript
castReversedBoolean(true); // false
castReversedBoolean('hello'); // false
castReversedBoolean(0); // true
```

## 4 задача

Напишите и экспортируйте функцию `determineEntrance()`, которая возвращает целое число - номер подъезда для заданной квартиры.

**Условия**

- В первом подъезде находятся квартиры с 1 по 20.
- Во втором с 21 по 48.
- В третьем с 49 по 90.
- При передаче несуществующего номера квартиры функция должна вернуть 0.

**Параметры**

- *num*: номер квартиры.

**Пример использования:**

```javascript
determineEntrance(21); // 2
determineEntrance(20); // 1
determineEntrance(95); // 0
```

## 5 задача

Напишите и экспортируйте функцию `getSum()`, которая возвращает сумму всех цифр целого положительного числа.

**Параметры**

- *num*: число, сумму цифр которого надо вернуть.

**Пример использования:**

```javascript
getSum(12345); // 15
getSum(0); // 0
getSum(10); // 1
```
