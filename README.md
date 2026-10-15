# Лабораторные работы по QGIS

Результаты лабораторных работ 5 и 6 по QGIS Training Manual 3.44: проекты, исходные учебные данные, промежуточные слои, карты и результаты проверок.

## Скачать и открыть

1. Скачайте [архив QGIS_Labs_5_6.zip](QGIS_Labs_5_6.zip) кнопкой **Download raw file** на странице файла или скачайте весь репозиторий через **Code → Download ZIP**.
2. Полностью распакуйте архив. Проекты нельзя открывать прямо из ZIP.
3. Откройте [index.html](QGIS_Labs_5_6/index.html) из распакованной папки в браузере: там инструкция и результаты.
4. Открывайте файлы `.qgz` в QGIS. Папки `data`, `Lab5` и `Lab6` переносите вместе — проекты используют относительные пути. Интернет для просмотра карт не нужен.

## Проекты

| Работа | Файл | Содержание |
| --- | --- | --- |
| 5 | [Lab_5.qgz](QGIS_Labs_5_6/Lab5/Lab_5.qgz) | Три полигона школьной территории, две линии маршрутов, изменение вершины |
| 6.1 | [Lab_6_1_Projections.qgz](QGIS_Labs_5_6/Lab6/Lab_6_1_Projections.qgz) | Перепроецирование на лету |
| 6.1 | [Lab_6_1_Buildings.qgz](QGIS_Labs_5_6/Lab6/Lab_6_1_Buildings.qgz) | Здания в исходной и проецированной системах координат |
| 6.1 | [Lab_6_1_Custom_CRS.qgz](QGIS_Labs_5_6/Lab6/Lab_6_1_Custom_CRS.qgz) | Пользовательская проекция Van der Grinten I |
| 6.2 | [Lab_6_2_Vector_analysis.qgz](QGIS_Labs_5_6/Lab6/Lab_6_2_Vector_analysis.qgz) | Буферы, пересечение, отбор 996 зданий по условиям урока |
| 6.3 | [Lab_6_3_Network.qgz](QGIS_Labs_5_6/Lab6/Lab_6_3_Network.qgz) | Кратчайший и быстрейшие пути, зона достижимости |
| 6.4 | [Lab_6_4_Statistics.qgz](QGIS_Labs_5_6/Lab6/Lab_6_4_Statistics.qgz) | Статистика, выборки 100 и 10 000 точек, интерполяция IDW |

В папке [reports](QGIS_Labs_5_6/reports) сохранены численные результаты, параметры алгоритмов и проверки. Экспорты карт находятся в [maps](QGIS_Labs_5_6/maps).

## Проверка

Результаты подготовлены через PyQGIS и GDAL. Все семь проектов повторно открыты после переноса в другую папку; проверены пути к данным, целостность GeoPackage и основные результаты вычислений. Проверки выполнены в QGIS 3.40.6 на Linux. Открытие именно в QGIS 3.44.14 на Windows пока не проверялось.

## Задания и данные

- [Работа 5 — создание векторных данных](https://docs.qgis.org/3.44/ru/docs/training_manual/create_vector_data/create_new_vector.html).
- [Работа 6 — модуль Vector Analysis, четыре урока](https://docs.qgis.org/3.44/ru/docs/training_manual/vector_analysis/index.html).
- [QGIS Training Data — release_3.44](https://github.com/qgis/QGIS-Training-Data/tree/release_3.44).
- [Лицензия учебных данных](QGIS_Labs_5_6/DATA_LICENSE.md).
