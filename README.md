# DEV_DB_03

Проектирование БД

# Разработка схемы данных на одну из заданных тем

выбрать тему, разработать схему данных, проанализировать предметную область

## Нормализация базы (домашнее задание)

первая нормальная форма:

- атомарны поля
  ! если нет, сразу добавляем дополнительные таблицы

# Вторая нормальная форма

* первичный ключ состоит из одной колонки (простой первичный ключ)
* каждый атрибут зависит от первичного ключа
  ! указываем ключевое поле (или формируем)

## Третья нормальная форма

один неключевой атрибут не должен функционально зависеть от другого не ключевого атрибута
! разбиваем таблицу на составные

## Рисуем диаграмму

- название таблицы
- ключевое поле (prime key)
- остальные колонки (поля)
- вторичные ключи (foreing keys)
- отражаем связи (одна ко многим)
- экспорт в *.png
