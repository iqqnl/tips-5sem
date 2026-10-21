# Домашнее задание 3. Акустическая диагностика подшипника

Решение задания: загрузка `Bearing.mat`, сегментация сигналов окнами с перекрытием,
синтетические смеси сигналов, RMS и 14 признаков окна, нормализация, создание трёх `RandomForestRegressor`.

## Структура
```
3_homework_bearing_diagnostics.ipynb   # выполненный ноутбук (все 7 проверок ✅)
data/Bearing.mat                       # данные
visualizations/                        # иллюстрации к заданиям 3 и 4
requirements.txt
```

## Запуск
```bash
pip install -r requirements.txt
jupyter notebook 3_homework_bearing_diagnostics.ipynb
```
Ноутбук нужно запускать из корня репозитория (путь к данным — `data/Bearing.mat`).
