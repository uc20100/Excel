# ДЗ по "Основы анализа данных в Excel (семинары)"

## Семинар 1. Основы работы с электронными таблицами

- Условие:  
1. Добавьте в таблицу книги файла Семинар1_данные.xlsx (прикреплен к семинару) столбец «Выручка по наименованию». В него добавьте данные по каждой книге следующего вида:  
Умножьте цену на количество проданных экземпляров и полученную сумму введите в столбец «Выручка по наименованию». Вы можете использовать калькулятор или иные методы, которые считаете нужными.
2. Найдите суммарную выручку и укажите ее в таблице под столбцом «Выручка по наименованию». Выделите ячейку с этим значением и в соседней ячейке слева напишите «Итого:»   

## Семинар 2. Применение формул. Функции

- Условие задания 1: Эдвард Лоренц говорил о знаменитом «эффекте бабочки»: «Бабочка, взмахивающая крыльями в Айове, может вызвать лавину эффектов, которые могут достигнуть высшей точки в дождливый сезон в Индонезии».
Предположим, что существует модель, где погода во время t всегда имеет значение между 0 и 1 и управляется выражением: $$F_{t + 1} = 4 * F_{t} * (1 - F_{t})$$ Вычислите для $F_1, F_2...F_{50}$ для двух начальных значений с помощью электронной таблицы:  
0,3  
0,300001  
Как Ваши вычисления иллюстрируют эффект бабочки?   

- Условие задания 2: В столбце F файла Cеминар2_дз2.xlsx содержатся коды товаров, а в столбце G – цены этих товаров. В столбцах М-О перечислены количество и цена, по которым магазин закупил различные товары. Определите общую стоимость закупок магазина.

- Условие задания 3: Мы участвуем в аукционе, где выставлена ценная картина. Картину приобретает тот, кто предложит самую высокую цену. Мы оценили картину в 100 000 рублей. В аукционе участвуют еще четыре человека. Участие в аукционе стоит 4000 рублей.  

    Создайте таблицу для решения задачи и напишите формулу, которая определит, получим ли мы картину (с учетом нашей ставки и ставки четырех конкурентов). 
    Рассчитайте общую стоимость участия в аукционе в зависимости от того, досталась нам картина или нет.

- Условие задания 4 (дополнительное):
Продажи нашего продукта зависят от нашей цены и цены конкурента следующим образом:
Если наша цена выше цены конкурента не менее чем на 300 рублей, мы продаем 500 единиц товара.
Если наша цена ниже цены конкурента не менее чем на 300 рублей, мы продаем 1500 единиц товара. Во всех остальных случаях мы продаем 1000 единиц товара.  

    Предположив, что все цены – это целые числа от 1 до 1000 рублей включительно, напишите формулу, которые вычисляют наши продажи этого продукта для любого возможного сочетания цен.  

    Используйте функцию ЕСЛИМН и ABS (для поиска модуля разницы)

## Семинар 3. Инструменты визуализации в MS Excel. Элементы статистики и прогнозирования

- Условие задания: В таблице файла Домашнее_Задание_1(1) приведены данные сети кондитерских о количестве продавцов и выручке за каждый месяц.  
    1. Создайте комбинированную диаграмму с вспомогательной осью для количества продавцов и выручки за каждый месяц.  
    2. Постройте диаграмму ежемесячной выручки и вставьте в диаграмму подписи данных.  
    3. Постройте диаграмму для количества продавцов и вставьте в диаграмму подписи данных.
    4. Укажите с помощью условного форматирования месяцы с наибольшей и наименьшей выручкой.

## Семинар 4. Анализ данных: часть 1  

- Условие задания:  
В таблице файла Семинар4_задача3 выполните следующие задания:  
1. Найдите все уникальные комбинации “имя-продукт-регион”, встречающиеся в сделках за первые три месяца 2020г.  
2. Найдите все сделки с тональной основой за первые три месяца 2020г., в которых цена за единицу продукции была выше средней цены за тональную основу за весь период.  
3. Постройте отчет по продажам продукции за 2021 год в западном филиале. Выделите каким либо образом сотрудника, который заключил сделки с наибольшей суммарной выручкой.  Постройте диаграмму, отражающую эффективность сотрудников в 2021 году в данном филиале  
4. Найдите самую крупную сделку (с точки зрения выручки) для каждого продукта.