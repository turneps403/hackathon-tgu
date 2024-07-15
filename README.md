## Задача по автоматизации предсказания общей продолжительности поездки в Нью-Йорке. 

![](/img/tgu-hackathon.png)

### Учебную задачу выполнили студенты команды №5

Работу можно посмотреть в файле **[Hackathon_5_group_TSU.ipynb](/Hackathon_5_group_TSU.ipynb)**

### Суть задачи

1. Обработка текущей базы данных, извлечения признаков из других датасетов и объединение их с основной базой данных, создание дополнительных признаков, кодирование категориальных признаков и масштабирование. Логарифмирование целевой переменной - продолжительность поездки.

2. Построение моделей для прогнозирование и сравнение моделей по логарифмированной RMSE. В рамках задачи построены следующие модели: LinearRegression, LinearRegression & PolynomialFeatures, RidgeRegression & PolynomialFeatures, DecisionTreeRegression, DecisionTreeRegression & GridSearch,                           RandomForest, GradientBoosting. 

3. Оценка моделей - логарифмированной RMS. Две модели переобучились:  LinearRegression & PolynomialFeatures, DecisionTreeRegression. Лучшую метрику на валидационной выборке продемонстрировала модель:  GradientBoosting.


### Используемые библиотеки Python

- numpy 
- pandas 
- matplotlib.pyplot 
- seaborn
- plotly 
- scipy.stats
- sklearn.


### Базы данных для выполнения задания

Скачать [здесь](https://cloud.mail.ru/public/3FSu/VqCMq7K3G)


### 6 этапов задачи

1. Знакомство с данными, базовый анализ, расширение данных. `Статус: Done`
2. Разведывательный анализ данных (EDA), визуализация, статистика. `Статус: Done`
3. Отбор и преобразование признаков, feature engeeniring. `Статус: Done`
4. Решение задачи регрессии: линейная регрессия и деревья решений.  `Статус: Done`
5. Решение задачи регрессии: ансамблевые методы и построение прогноза. `Статус: Done`
6. XGBoost. `Статус: Done`