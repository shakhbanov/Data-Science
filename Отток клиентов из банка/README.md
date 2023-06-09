### Цель проекта

Провести исследование с целью построения модели машинного обучения, которая поможет прогнозировать уход клиентов из «Бета-Банка» в ближайшее время.

Результаты исследования позволят маркетологам сохранить текущих клиентов, т.к. это дешевле, чем привлекать новых.

Входные данные: исторические данные о поведении клиентов и расторжении договоров с банком.


### Задачи проекта

1. Изучить данные.
2. Подготовить данные.
3. Исследовать баланс классов, обучить модель без учёта дисбаланса.
4. Улучшить качество модели, учитывая дисбаланс классов. Обучить разные модели и найти лучшую.
5. Протестировать лучшую модель.
6. Проверить гипотезы.
7. Написать общий вывод.

Значение метрики *F1*-мера должно быть доведено до 0.59.

В ходе проведения исследования необходимо проверить несколько гипотез:

- Гипотеза 1: лучшая модель на валидационной выборке - модель случайного леса;
- Гипотеза 2: значение метрики *F1*-мера лучшей модели больше 0.59;
- Гипотеза 3: значение метрики *AUC-ROC* повышается с ростом значения *F1*-меры;
- Гипотеза 4: лучшая модель чаще ошибается, прогнозируя клиентов, которые ушли из банка.


### Навыки и инструменты

- matplotlib.pyplot
- numpy
- pandas
- python
- random
- seaborn
- sklearn.dummy
- sklearn.ensemble
- sklearn.linear_model
- sklearn.metrics
- sklearn.model_selection
- sklearn.preprocessing
- sklearn.tree
- sklearn.utils


### Общий вывод

Гипотезы 1, 2, 3 и 4 подтвердились.