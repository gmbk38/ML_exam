# ML_exam
Практическая часть экзамена машинок

Экзамен по дисциплине «Технологии анализа данных и машинное обучение», состоит из теоретической и практической частей. Данная модель устанавливает следующую схему выставления баллов промежуточной аттестации:

- 40 баллов текущего контроля определяются по итогам изучения всей дисциплины;

- 20 баллов из 60 отводится для выполнения теоретического задания;

- 40 баллов выставляются за выполнение практического задания.

Практическая часть представляет собой задачу по анализу конкретного датасета. Для каждого задания будет необходимо: 
Загрузить датасет в Python.
Описать набор данных и решаемую задачу.
Выделить целевую переменную и факторные переменные.
Удалить ненужные данные, проанализировать отсутствующие значения.
Прокомментировать количественные параметры датасета.
Разбить выборку на обучающую и тестовую.
Работа по вариантам.
# Вариант 1. Очистка данных и обучение моделей.

Данный вариант предполагает фокусировку на обучении нескольких видов моделей обучения с учителем. В зависимости от набора данных, может предполагаться задача классификации и регрессии. Необходимо после минимальной подготовки датасета к обучению обучить несколько моделей и сравнить их эффективность.
# Вариант 2. Описательный анализ и визуализация данных.

Данный вариант предполагает фокусировку на исследовании данных и визуализации. При решении этого варианта следует провести как можно более подробный описательный анализ данных с использованием максимального спектра средств визуализации. При этом следует делать значимые выводы об обнаруженных в данных закономерностях.
# Вариант 3. Построение модели и оптимизация гиперпараметров.

Данный вариант предполагает фокусировку на процессе улучшения эффективности модели обучения с учителем. Студенту следует подготовить датасет к обучению, обучить одну из моделей с учителем со значениями гиперпараметров по умолчанию, получить значение эффективности. После этого вручную или автоматически подобрать значения гиперпараметров таким образом, чтобы получить максимальный прирост эффективности.
# Вариант 4. Выбор признаков.

Данный вариант предполагает фокусировку на улучшении модели путем ввода новых признаков в модель. Следует подготовить модель к обучению, обучить модель и зафиксировать начальный уровень эффективности. Затем следует исследовать влияние исключения существующих и введения новых признаков в модель на эффективность. Как вариант можно рассматривать введение полиномиальных признаков. Следует стремиться к максимальному увеличению эффективности модели.
# Вариант 5. Исследование влияния обучения без учителя на эффективность обучения.

Данный вариант предполагает фокусировку на использовании методов обучения без учителя для ускорения или повышения эффективности обучения с учителем. Следует подготовить модель к обучению, обучить модель и зафиксировать начальный уровень эффективности. Затем следует попробовать применить понижение размерности, обнаружение аномалий или кластеризацию (в любой комбинации) для трансформации исходного датасета. В конце работы следует сделать значимый вывод об изменении скорости и эффективности обучения с учителем.

Для выполнения кейса задачи, рекомендуется использовать язык программирования Python и специализированные библиотеки для анализа данных и машинного обучения.
Студент должен прислать рабочий notebook с решением кейса задачи, комментариями кода и аналитическими выводами до конца экзамена на электронную почту преподавателя.
# Критерии оценки практической экзаменационной работы:

- Структурированность отчета. В работе должна прослеживаться четкая структура - подготовительный этап, анализ данных, построение простых моделей, сравнение и анализ моделей, выводы, построение моделей с учетом выводов, итоговый результат.
- Наличие выводов. Работа должна содержать текстовые замечания, поясняющие каждый шаг работы студента: что делается, зачем и какую информацию это нам дает. Оценивается полнота и адекватность выводов.
- Визуализация. Работа должна демонстрировать навыки студента визуализировать информацию. Особенно на этапах описательного анализа и анализа обучаемости модели. Оценивается разнообразие, наглядность и информативность визуализации.
- Использование метрик эффективности. Оценивается разнообразие и адекватность задаче примененных метрик эффективности (включая время обучения) а также полнота сравнения и правильность выводов из сравнения моделей по разным метрикам.
- Валидность результатов. Студент должен продемонстрировать умение оценивать достоверность измерения метрик моделей и повышать ее с использованием перекрестной проверки (кросс-валидации). Использование k-fold cross validation является предпочтительным методом измерения эффективности модели. Если происходит выбор модели, то ее итоговая эффективность должна измеряться на чистом наборе данных.

Список датасетов, использующихся на экзамене:

https://www.kaggle.com/uciml/mushroom-classification
https://www.kaggle.com/lodetomasi1995/income-classification
https://www.kaggle.com/uciml/glass
https://www.kaggle.com/uciml/german-credit
https://www.kaggle.com/zaurbegiev/my-dataset
https://www.kaggle.com/kaushiksuresh147/customer-segmentation
https://www.kaggle.com/deepu1109/star-dataset
https://www.kaggle.com/vinesmsuic/star-categorization-giants-and-dwarfs
https://www.kaggle.com/shebrahimi/financial-distress
https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction
https://www.kaggle.com/amir75/caesarean-section-classification
https://www.kaggle.com/sachinsharma1123/performance-prediction
https://www.kaggle.com/ninzaami/loan-predication
https://www.kaggle.com/caparrini/beatsdataset
https://www.kaggle.com/zhiruo19/covid19-symptoms-classification
https://www.kaggle.com/kunalvsingh93/banking-modelclassification
https://www.kaggle.com/mansoordaku/ckdisease
https://www.kaggle.com/mnassrib/telecom-churn-datasets
https://www.kaggle.com/akshayksingh/kidney-disease-dataset
https://www.kaggle.com/henriqueyamahata/bank-marketing
https://www.kaggle.com/maajdl/yeh-concret-data
https://www.kaggle.com/hellbuoy/car-price-prediction
https://www.kaggle.com/rhuebner/human-resources-data-set
https://www.kaggle.com/loveall/appliances-energy-prediction
https://www.kaggle.com/elikplim/forest-fires-data-set
https://www.kaggle.com/nandvard/microsoft-data-science-capstone
https://www.kaggle.com/shebrahimi/financial-distress
https://www.kaggle.com/aungpyaeap/beauty
https://www.kaggle.com/vbmokin/ammonium-prediction-in-river-water
https://www.kaggle.com/veer06b/marrket-mix-dataset
