# Расчет ректификационной установки и теплообменников к ней

[![Build and Deploy](https://github.com/kdavjd/rectification_project/actions/workflows/build-and-deploy.yml/badge.svg)](https://github.com/kdavjd/rectification_project/actions/workflows/build-and-deploy.yml)

---
Сайт по которому доступно приложение.
[nuclearexistence.ru](http://nuclearexistence.ru/)

### Описание проекта

Автоматический расчёт ректификиционной колонны и подбор теплообменников к ней. Приведёный расчет выполнен без учета влияния на основные размеры
ректификационной колонны ряда явлений(таких как неравномерность распределения жидкости при орошении, обратное перемениваение, тепловые эффекты и др.),
что иногда может внести в расчет существенные ошибки; однако позволяет наглядным способом изучать влияние состава разделяемой смеси,
флегмового числа, расхода и прочих параметров на требуемые габариты установки.

### Навигация по папкам и файлам

Тарельчатую колонну можно посчитать в файле 'plate_column.ipynb'

Насадочную колонну можно посчитать в файле 'filling_column.ipynb'

В папке 'data' хранятся свойства некоторых водных растворов неорганических веществ и свойства некоторых органических веществ. К большинству этих данных можно получить доступ, вызвав переменную ph_organic в любом из файлов колонн.

В папке 'l_v' хранятся диаграмы равновесия жидкость-пар для некоторых пар веществ.

В папке 'tables' находятся ГОСТы на теплооменники, колонны и тарелки колонн, по которым подбирается и считается конструкция установки.

в файле 'processing_frames' собраны данные равновесия вода-'компонент'. Красивые фигуры, интересные графики

### Какие единицы измерения в расчете?

Основная логика изложения расчета взята из Дытнерского. Все единицы измерения соответствуют примерам из этого источника.

### Список использованной литературы

1. Основные процессы и аппараты химической технологии. Пособие по проектированию. Под ред. Ю. И. Дытнерского, 2-ое изд., перераб. и дополн. – М.: Химия, 1991. – 496с.
2. Павлов К. Ф., Романков П. Г., Носков А. А. Примеры и задачи по курсу процессов и аппаратов химической технологии. М.: Химия, 1976. – 552с.
3. Коган В. Б., Фридман В. М., Кафаров В. В. Равновесие между жидкостью и паром. Справочное пособие. Книга 1. М – Л, Наука (Ленингредское отделение), 1996. – 640с.
4. Касаткин А. Г. Основные процессы и аппараты химической технологии. Изд. 9-е. М.: Химия, 1973 – 750с.
5. Свойства веществ. Справочное пособие /РХТУ им. Д. И. Менделеева. Сост. В. Н. Бобылев, М.: 1996. – 24с.
6. Варгафтик В. Д. Справочник по теплофизическим свойствам газов и жидкостей. 2-ое изд., перераб. и дополн. – М.: Наука, 1972 – 720с.
7. Лащинский А. А., Толчинский А. Р. Основы конструирования и расчета химической аппаратуры. Справочник. 2-ое изд., перераб. и доп. – Л.: Машиностроение, 1970. – 752с.
8. Александров И.А. Ректификационные и абсорбционные аппараты. Методы расчета и основы конструирования 3-е изд. перераб. М.: Химия, 1978. - 280 с.

### Выводы

Получился тренажер, на котором можно изучить влияние различных параметров на расчет. Переменные удобно изменять и изучать на их основании многие зависимости, не затронутые этим проектом.


Спасибо за внимание!
