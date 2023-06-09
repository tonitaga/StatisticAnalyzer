# STATISTIC ANALYZER by tonitaga

---

## Содержание

1. [Разработчики](#разработчики)
2. [Идея проекта](#идея-проекта)
3. [Как оно выглядит?](#как-оно-выглядит)
4. [QCustomPlot](#qcustomplot)

---

<p align="center">
<img src="misc/images/graph.png" style="width: 35vw; min-width: 300px;" />
</p>

---

### Разработчики:
- Губайдуллин Нурислам

---

### Идея проекта

* Основной идеей стало автоматизировать выполнение лабораторной работы в Казанском Авиационном Институте по предмету Основы Технологии Машиностроения
* На выполнение данного приложения подтолкнула любовь в своим одногруппникам и любовь к математике

---

### Как оно выглядит?

* За основу берется файл с расширением .txt, где находятся данные выборки записанные через пробел либо на новой строке
* Приложение считывает выборку из файла и рассчитывает основные данные математической статистики по текущей выборке

<p align="center">
<img src="misc/images/loaded_statistic.png" style="width: 35vw; min-width: 400px;" />
</p>

* Нажав кнопку "Разбить выборку" заранее выбрав чуть выше на сколько интервалов, можно получить график практического распределения по интервалам текущей выборки

<p align="center">
<img src="misc/images/build_intervals.png" style="width: 35vw; min-width: 400px;" />
</p>

* Нажав кнопку "Нормальное распределение" заранее построив график практического распределения, построится график приведенного (к практическому графику) нормального распределения

<p align="center">
<img src="misc/images/normal_distribution.png" style="width: 35vw; min-width: 400px;" />
</p>

* Нажав кнопку "Получить интервалы" заранее разбив выборку на интервалы, можно получить файл с интервалами в формате .txt

<p align="center">
<img src="misc/images/save_intervals.png" style="width: 35vw; min-width: 400px;" />
</p>

* Нажав кнопку "Сортированная статистика" можно получить файл с отсортированной выборкой в формате .txt

<p align="center">
<img src="misc/images/sorted_statistic.png" style="width: 35vw; min-width: 400px;" />
</p>

---

### QCustomPlot

* Графики строятся при помощи библиотеки QCustomPlot
* Cайт разработчиков [QCustomPlot](https://www.qcustomplot.com/)

---

#### © tonitaga (Губайдуллин Нурислам) 29.05.2023