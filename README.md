# DA_lab2# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #2 выполнил:
- Пикулин Марк Андреевич
- РИ-210933
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Познакомиться с программными средствами для организции передачи данных между Google, Unity и Python

## Задание 1
### Реализовать совместную работу и передачу данных в связке Python - Google-Sheets – Unity. При выполнении задания используйте видео-материалы и исходные данные, предоставленные преподавателя курса.
- В облачном сервисе google console подключить API для работы с google sheets и google drive.
- Реализовать запись данных из скрипта на python в google-таблицу. Данные описывают изменение темпа инфляции на протяжении 11 отсчётных периодов, с учётом стоимости игрового объекта в каждый период.
- Создать новый проект на Unity, который будет получать данные из google-таблицы, в которую были записаны данные в предыдущем пункте.
- Написать функционал на Unity, в котором будет воспризводиться аудио-файл в зависимости от значения данных из таблицы.

### Сохранение данных в GoogleSheets:
![1](https://user-images.githubusercontent.com/104256775/209380558-6beec5d0-f085-4dd7-8dc1-c2348db401dd.png)
### Код для создания данных в GoogleSheets
![2](https://user-images.githubusercontent.com/104256775/209380581-c590ad8e-081a-4304-bd7b-6935ebc4835b.png)
### Код для вызова звука в Unity
![3](https://user-images.githubusercontent.com/104256775/209380699-759ee133-e8eb-499f-afa0-ace79e878c03.png)
![31](https://user-images.githubusercontent.com/104256775/209380764-2ec09e77-5eed-4e0e-8a36-461f98e93f52.png)
![32](https://user-images.githubusercontent.com/104256775/209380869-0a681123-16ff-415e-b688-1b3f59070a38.png)
![33](https://user-images.githubusercontent.com/104256775/209380880-298475b4-c6f3-48c7-b136-bb54b9283dd6.png)

### Демонтрация работы в Unity
![4](https://user-images.githubusercontent.com/104256775/209381019-fa2c8781-ea8e-437e-a87a-a03223ab4d5f.png)





## Задание 2
### Реализовать запись в Google-таблицу набора данных, полученных с помощью линейной регрессии из лабораторной работы № 1. 
### Выполение работы:
![5](https://user-images.githubusercontent.com/104256775/209381358-93d4b8e4-33b5-4271-b117-edc899094533.png)
![51](https://user-images.githubusercontent.com/104256775/209381399-85f01b81-15be-4cb8-b615-23bd704369d5.png)
![52](https://user-images.githubusercontent.com/104256775/209381426-387565e7-7ddb-4b21-ab01-d8f44112fbeb.png)
![53](https://user-images.githubusercontent.com/104256775/209381455-26b5c168-d7ac-431d-89ac-7e0d462e752f.png)

### Результат работы:
![6](https://user-images.githubusercontent.com/104256775/209381486-cdc6649b-61c5-46a6-9b26-7e14f7cd472e.png)



## Вывод
Я изучил совместную работу Python, GSheets и Unity, сделав воспроизведение звуковых эффектов в Unity, зависящих от изложенных в Sheets данных; записал в таблицу данные из предыдущей лабораторной работы.
