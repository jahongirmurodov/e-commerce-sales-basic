# E-commerce Sales Data Analysis

## Overview
This project focuses on performing exploratory data analysis (EDA) on an e-commerce dataset. The goal was to analyze sales performance, identify key patterns, and visualize important business metrics.

## Problem Statement
The objective was to understand sales behavior across products, categories, and time, as well as to identify top-performing items and potential inefficiencies in sales distribution.

## Objectives
- Perform data cleaning and preprocessing
- Generate new meaningful features
- Analyze sales performance
- Visualize key metrics and trends

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Description
The dataset was synthetically generated and includes:
- Order ID
- Product name
- Category
- Price
- Quantity
- Date

## Methodology

### 1. Data Generation
- Created a dataset with 300 records
- Simulated product categories and pricing
- Introduced missing values for realism

### 2. Data Preprocessing
- Checked for missing values and removed them
- Verified duplicates
- Ensured correct data types

### 3. Feature Engineering
- Created `total` (price × quantity)
- Extracted `month` from date
- Created `sales_group` (Low / Medium / High)

### 4. Data Analysis
- Calculated descriptive statistics
- Identified top-performing products
- Analyzed monthly sales trends
- Evaluated sales distribution across categories

### 5. Data Visualization
- Histogram of price distribution
- Boxplot of order totals by product
- Barplot of total sales per product
- Line chart of monthly sales
- Countplot of sales groups

## Results & Insights
- The dataset was successfully cleaned and prepared for analysis
- The most profitable product category was identified (Headphones)
- Peak sales occurred between months 2 and 4
- Detected outliers in certain product categories (e.g., Phones)
- Majority of transactions fall into the "High" sales group

## Key Takeaways
- Even simple EDA provides valuable business insights
- Feature engineering significantly improves analysis quality
- Visualization helps identify patterns quickly

## Possible Improvements
- Use real-world dataset instead of synthetic data
- Apply advanced analytics (correlation, clustering)
- Build predictive models (sales forecasting)
- Create an interactive dashboard (Power BI / Tableau)



# Анализ продаж интернет-магазина

## Обзор проекта
Данный проект посвящен проведению разведочного анализа данных (EDA) для интернет-магазина. Цель — изучить поведение продаж, выявить ключевые закономерности и визуализировать основные метрики.

## Постановка задачи
Необходимо проанализировать продажи по товарам, категориям и времени, определить наиболее прибыльные позиции и выявить особенности распределения продаж.

## Цели проекта
- Провести очистку и предобработку данных  
- Создать новые признаки  
- Выполнить анализ продаж  
- Визуализировать ключевые показатели  

## Используемые технологии
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

## Описание данных
Данные были сгенерированы искусственно и включают:
- ID заказа  
- Название товара  
- Категорию  
- Цену  
- Количество  
- Дату  

## Методология

### 1. Генерация данных
- Создан датасет из 300 записей  
- Смоделированы категории товаров и цены  
- Добавлены пропуски для реалистичности  

### 2. Предобработка данных
- Обнаружены и удалены пропуски  
- Проверены дубликаты  
- Приведены типы данных  

### 3. Feature Engineering
- Создан признак `total` (общая сумма заказа)  
- Выделен `month` из даты  
- Добавлен `sales_group` (Low / Medium / High)  

### 4. Анализ данных
- Рассчитана описательная статистика  
- Определены топовые товары  
- Проанализированы продажи по месяцам  
- Исследовано распределение продаж  

### 5. Визуализация
- Гистограмма распределения цен  
- Boxplot по сумме заказов  
- Barplot по продажам товаров  
- Линейный график продаж по месяцам  
- Countplot категорий продаж  

## Результаты и выводы
- Данные успешно очищены и подготовлены  
- Самый прибыльный товар — Headphones  
- Пиковые продажи приходятся на 2–4 месяцы  
- Обнаружены выбросы (например, Phone)  
- Большинство продаж относятся к категории "High"  

## Ключевые выводы
- Даже базовый EDA позволяет получить ценные инсайты  
- Feature engineering значительно улучшает анализ  
- Визуализация упрощает поиск закономерностей  

## Возможные улучшения
- Использовать реальные данные  
- Добавить более глубокий анализ  
- Построить ML-модель (прогноз продаж)  
- Создать интерактивный дашборд  
