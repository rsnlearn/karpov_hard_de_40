# Проект к блоку проектирование DWH

Задача перенести в КХД данные для БП проверки и утилизации товаров при получении при переходе ответственности от поставщика к получателю.

По результату проверки может быть принято одно из решений:
Полная приемка
Полная утилизация
Полный возврат
Переборка - Частичная приемка с утилизацией
Переборка - Частичная приемка с возвратом

Исходные данные представлены в виде набора excel файлов.

По требованиям структура витрин для аналитики должна соответствовать предоставленным файлам.

По результатам предварительного анализа, исходные источники можно разделить на две группы:
1. Реестр проверок
2. Реестр утилизации

Реестр проверок:
1.	Номер проверки
2.	Дата проверки
3.	Страна происхождения
4.	Место приемки
5.	Сюрвейер
6.	Договор
7.	Отправитель
8.	Получатель
9.	Заказ
10.	Партия
11.	Позиция
12.	Категория 1
13.	Категория 2
14.	Категория 3
15.	Категория 4
16.	Транспортное средство
17.	Способ доставки
18.	Дата проверки
19.	Дата прибытия
20.	Путь к файлу отчета о проверке
21.	Тип проверки (доверительная/полная/стандартная)
22.	Результат проверки (прием/возврат)
23.	Стоимость проверки

Реестр утилизации:
1.	Компания утилизатор
2.	Номер договора
3.	Позиция
4.	Место утилизации
5.	Объем утилизации
6.	Цена утилизации за единицу
7.	Ед. измерения
8.	Стоимость утилизации
9.	Планируемая дата утилизации
10.	Дата утилизации
11.	Путь к файлу отчета об утилизации


Диаграмма со структурой источников:

![Диаграмма со структурой источников](http://plantuml.com:80/plantuml/png/3SX1Zi8m343HVKynSu6wI2mG4g8tYKnYDOR4YMo7Nf_i_d-xEQgFMfP_bbX6eg7bBxjtkmCedkl1diTh66biuYI-nbP1JGgX2dnGU_k6Z9f2ed3Te28BR9UGpZp5-9Xt2rtRcw83QG8MwxEvYGKMTiQozb7BCsBCz92sx2HfmWy0?cache=no)

![Диаграмма со структурой источников через сервис](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/rsnlearn/karpov_hard_de_40/main/01_dwh_design/08_project/erd/inspections_initial.puml)

