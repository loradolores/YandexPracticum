# YandexPracticum

## Проект 1. Исследование объявлений о продаже квартир

### __Цели:__

Провести исследование с целью выявить интересные особенности и зависимости, которые существуют на рынке недвижимости.

Результаты исследования будут учтены при построении модели зависимости стоимости объектов от различных параметров на рынке недвижимости.

### __Описание проекта:__

В нашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений за несколько лет о продаже квартир в Санкт-Петербурге и соседних населённых пунктах. Нужно научиться определять рыночную стоимость объектов недвижимости.

Наша задача — выполнить предобработку данных и изучить их, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

О каждой квартире в базе содержится два типа данных: добавленные пользователем и картографические. Например, к первому типу относятся площадь квартиры, её этаж и количество балконов, ко второму — расстояния до центра города, аэропорта, ближайшего парка и водоёма.

## Проект 2. Статистический анализ данных

### __Цели:__

Провести исследование и проанализировать поведение клиентов с целью выявить тариф, который приносит больше денег.

Результаты исследования позволят коммерческому департаменту скорректировать рекламный бюджет.

### __Описание проекта:__

Мы аналитики компании «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

Нам предстоит сделать предварительный анализ тарифов на небольшой выборке клиентов. В нашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018-й год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

## Проект 3. Исследование популярности компьютерных игр

### __Цели:__

Провести исследование с целью выявить определяющие успешность компьютерных игр закономерности.

Результаты исследования позволят сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

### __Описание проекта:__

Мы работаем в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, _Xbox_ или _PlayStation_). Нам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

Перед нами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и мы планируем кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируем ли мы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.

В наборе данных попадается аббревиатура _ESRB (Entertainment Software Rating Board)_ — это ассоциация, определяющая возрастной рейтинг компьютерных игр. _ESRB_ оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».

## Проект 4. Рекомендация тарифов

### __Цели:__

Провести исследование с целью предложить пользователям новый тариф «Смарт» или «Ультра» на основании их поведения.

Результаты исследования позволят специалистам выбрать самую качественную модель, которая выберет подходящий тариф.

### __Описание проекта:__

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

В нашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных была сделана в проекте «Статистический анализ данных».

Построим модель с максимально большим значением *accuracy*. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверим *accuracy* на тестовой выборке.

## Проект 5. Отток клиентов

### __Цели:__

Провести исследование с целью прогнозирования ухода клиентов из «Бета-Банка» в ближайшее время.

Результаты исследования позволят маркетологам сохранить текущих клиентов, т.к. это дешевле, чем привлекать новых.

### __Описание проекта:__

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Спрогнозируем, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Построим модель с предельно большим значением _F1_-меры. Чтобы проект стал успешным, доведём метрику до 0.59. Проверим F1-меру на тестовой выборке.

Дополнительно измерим _AUC-ROC_, сравним её значение с _F1_-мерой.

## Проект 6. Выбор локации для скважины

### __Цели:__

Провести исследование с целью построения модели машинного обучения, которая поможет определить регион, где добыча нефти принесёт наибольшую прибыль.

Результаты исследования позволят увеличить прибыль добывающей компании «ГлавРосГосНефть».

### __Описание проекта:__

Допустим, мы работаем в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину.

Нам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Построим модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируем возможную прибыль и риски техникой Bootstrap.

Шаги для выбора локации:

- В избранном регионе найдём месторождения, для каждого определяем значения признаков;
- Построим модель и оценим объём запасов;
- Выберем месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
- Прибыль равна суммарной прибыли отобранных месторождений.

## Проект 7. Восстановление золота из руды

### __Цели:__

Подготовить прототип модели машинного обучения для компании [«Цифра»](https://www.zyfra.com/ru/ "https://www.zyfra.com/ru/").

Результаты исследования позволят предсказать коэффициент восстановления золота из золотосодержащей руды. Это поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

### __Описание проекта:__

Подготовим прототип модели машинного обучения для компании [«Цифра»](https://www.zyfra.com/ru/ "https://www.zyfra.com/ru/"). Компания разрабатывает решения для эффективной работы промышленных предприятий.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Используем данные с параметрами добычи и очистки.

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

Нам нужно:

- Подготовить данные;
- Провести исследовательский анализ данных;
- Построить и обучить модель.
Чтобы выполнить проект, будем обращаться к библиотекам pandas, matplotlib и sklearn. Нам поможет их документация.
