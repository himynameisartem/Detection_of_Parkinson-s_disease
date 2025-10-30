# Обнаружение болезни Паркинсона с помощью XGBoost

## Описание

Этот проект использует методы Data Science для предсказания болезни Паркинсона на ранней стадии. В качестве основного алгоритма машинного обучения используется **XGBoost**. Данные проходят предварительную обработку, включая нормализацию признаков с помощью `StandardScaler` из библиотеки `sklearn`.

Основная цель проекта — достичь точности предсказания более 95% на тестовой выборке.

## Датасет

Используется датасет [UCI ML Parkinsons](https://archive.ics.uci.edu/ml/datasets/Parkinsons). Он содержит ряд биомедицинских измерений голоса, где одна из колонок (`status`) указывает на наличие у пациента болезни Паркинсона (1) или на его здоровье (0).

## Как запустить

1.  Убедитесь, что у вас установлен Python и необходимые библиотеки (pandas, numpy, sklearn, xgboost, matplotlib, seaborn).
2.  Запустите Jupyter Notebook `Detection_of_Parkinson's_disease.ipynb`.
3.  Скачайте в корневую папку [Датасет](https://archive.ics.uci.edu/ml/datasets/Parkinsons)
4.  Выполните все ячейки последовательно, чтобы обучить модель и получить результат.

## Результаты

Финальная модель `XGBClassifier` с подобранными параметрами и зафиксированным `random_state` для воспроизводимости достигла следующей точности на тестовой выборке (20% от данных):

**Точность: 97.44%**

---

# Parkinson's Disease Detection using XGBoost

## Description

This project uses Data Science methods to predict Parkinson's disease at an early stage. The core machine learning algorithm used is **XGBoost**. The data is preprocessed, including feature scaling using `StandardScaler` from the `sklearn` library.

The main goal of the project is to achieve a prediction accuracy of over 95% on the test set.

## Dataset

The project uses the [UCI ML Parkinsons dataset](https://archive.ics.uci.edu/ml/datasets/Parkinsons). It contains a range of biomedical voice measurements, where one of the columns (`status`) indicates whether the subject has Parkinson's disease (1) or is healthy (0).

## How to Run

1.  Ensure you have Python and the required libraries installed (pandas, numpy, sklearn, xgboost, matplotlib, seaborn).
2.  Download
3.  Launch the Jupyter Notebook `Detection_of_Parkinson's_disease.ipynb`.
4.  Execute all cells in order to train the model and see the results.

## Results

The final `XGBClassifier` model, with tuned parameters and a fixed `random_state` for reproducibility, achieved the following accuracy on the test set (20% of the data):

**Accuracy: 97.44%**
