# Личный кабинет пользователя тренажерного зала

## Содержание


[Введение](#введение)

1. [Описание предметной области](#предметная_область)

1.1 [Проблематика](#проблематика)

1.2 [Цели и задачи](#цели_и_задачи)

1.3 [Варианты решения проблемы](#решение_проблемы)

2. [Сравнительный анализ существующих решений](#анализ)

3. [Разработка информационной системы](#разработка)

3.1 [Проектирование информационной системы](#проектирование)

3.2 [Реализация информационной системы](#реализация)

4. [Тестирование информационной системы](#тестирование)

[Заключение](#заключение)

[Список использованных источников](#ссылки)

***

## Введение <a name="введение"></a>

Темой проекта является информационная система "Личный кабинет пользователя тренажёрного зала", так как в последнее время наметилась тенденция к здоровому образу жизни и всё больше людей устремляют свой взор в сторону правильного питания и тренировок. Фитнес услуги, как никогда, сегодня пользузуются огромной популярностью. Именно поэтому идея создания данной информационной системы отличается актуальностью и позволяет построить успешный выгодный бизнес.

***

## 1 Описание предметной области <a name="предметная_область"></a>

Человек, заинтересованный в посещении тренажёрного зала, заходит на сайт и может просмотреть ленту новостей, зарегистрироваться, получить абонемент и войти в личный кабинет или, если у него уже есть учётная запись, сразу попасть в личный кабинет. Далее он может выбрать себе тренера, посмореть его расписание и записаться на занятие. После встречи посетитель может оценить его работу и оставить комментарий.

Администратор сайта занимается выдачей и продлением абонементов и составлением расписания, согласованного с тренерами. Кроме того, администратор ведёт ленту новостей, в которую добавляет всё, что пожелает нужным, это могут быть какие-либо изменения в работе клуба, фото, видео, скидки и спец.предложения. Помимо всего вышеупомянутого администратор составляет расписание, которое обязательно должно быть согласованно с каждым тренером заранее.

Что касается самого тренера, то он заходит в личный кабинет и может видеть ту же самую ленту новостей, своё расписание с занятыми и свободными днями и информацию о записавшемся.

***

## 1.1 Проблематика <a name="проблематика"></a>

Сторонники здорового образа жизни знают о пользе фитнеса, но не понимают, какой зал или программу занятий выбрать. Чтобы лучше в этом разобраться, потенциальные клиенты ищут информацию онлайн, сравнивают сайты различных фитнес центров. Поэтому создать качественную спортивную информационную систему важно для привлечения новых клиентов и удобства нынешних пользователей. Информационные системы нужны для поддержания доверия, упрощения взаимодействия между пользователем и клубом (например, через личный кабинет), предоставления информации об услугах, а также аккредитации спортивных тренеров.

Как уже говорилось выше, чтобы выбрать подходящий спортзал, пользователи сравнивают их социальные сети, сайты, и выбирают тот клуб, который предоставляет полезную информацию о компании, предлагает помощь онлайн.

***

## 1.2 Цели и задачи <a name="цели_и_задачи"></a>

Целью данного проекта является создание такой информационной системы спортивного клуба, который заинтересует любого человека, посетившего страницу.

Задачи проекта.
1. Информация, при всём её многообразии, должна подаваться просто и доступно. 
2. Нужно передать атмосферу клуба. 
3. Необходимо показать, что услуги предназначаются всем, кто в них заинтересован - для профессиональных спортсменов, для тех, кто может посещать занятия в обеденный перерыв, после работы, по выходным или рано утром.

***

## 1.3 Варианты решения проблемы <a name="решение_проблемы"></a>

Чтобы заинтересовать потенциального посетителя фитнес-центра, необходимо рассказать о всех услугах на странице клуба и проиллюстрировать их фотографиями. Чтобы побудить пользователя выбрать именно этот спортзал, недостаточно просто написать, какие тренажёры размещены в нём. Нужно разместить их изображения на странице, рассказать о применении различных типов оборудования.

Кроме того, следует разместить информацию о тренерах и их достижениях. Это поможет показать экспертность, завоевать доверие. Информация о фитнес тренере позволит клиенту поближе с ним познакомиться, а при интеграции с социальными сетями инструктора (например, Инстаграм) приведёт его подписчиков на сайт клуба.

Главным преимуществом данной информациооной системы может стать расписание тренировок с возможностью онлайн записи. Эта функция позволит клиенту сразу выбрать удобное время у понравившегося тренера, без необходимости оставлять заявку или звонить операторам.

Также пользователи оценят возможность оформить клубные карты онлайн, получить скидку по специальному промо-коду. А информативные, полезные статьи, а также видео для каждого сегмента целевой аудитории помогут выделиться среди других фитнес центров.

***

## 2 Сравнительный анализ существующих решений <a name="анализ"></a>

Рассмотрим два уже существующих сайта потенциальных конкурентов и сравним их с данной информационной системой по некоторым критериям. Не указывая реальных названий, обозначим их как №1, №2 и №3. Последний явлется разрабатываемой ИС.
    
 
|Зал|                                    Структура                                     |
|№1|Приходится делать много переходов и «кликов», чтобы докопаться до нужной информации|
|№2|Очень сложная структура сайта, возникает путаница в голове                         |
|№3|Простая и понятная структура, всю важную информацию можно найти на главной странице|






|--------------------------------------------------------------------------------------|
|                                       Услуги                                         |
|--------------------------------------------------------------------------------------|
|№1|Нет описания, длительности, для кого больше подходит, степени сложности и расценок|
|№2|Популярные фитнес-направления не имеют описания. Хочется подробнее прочитать о занятиях – как проходят, на что направлены|
|№3|Полное описание всех услуг и занятий: краткое описание занятия, ведущий тренер, номер зала, цена, выбор времени записи|




1. Дизайн:
У фитнес-клуба №1 стандартный и ничем не примечательный дизайн, у спортклуба №2 
***

## 3 Разработка информационной системы<a name="разработка"></a>

Изучаем потребности клиентов, исследуем конкурентов. Продумываем структуру и дизайн. Согласовываем всё с заказчиком. Тестируем и передаём заказчику. В конце записываем обучающее видео, чтобы сотрудники сами могли администрировать информационную систему.

***

## 3.1 Проектирование информационной системы <a name="проектирование"></a>

Проектирование началось с анализа опыта работы информационных систем других тренажёрных залов, выявления их плюсов и минусов. После, на основе полученных данных, необходимо было создать собственную ИС так, чтобы с момента знакомства с ним посетитель убеждался в выгодности и привлекательности предложения фитнес-клуба.

Что для этого сделали: 
1. Изучили симпатии и антипатии клиентов в отношении современных информационных систем. 
2. Проанализировали конкурентов, которых в зоне данного спортивного клуба обнаружилось предлстаточно. Однако у кого-то из них устаревший дизайн, неоправданно завышенные цены, у некоторых она оказалась давно уже заброшенной. 
3. Была определена целевая аудитория посетителей. Ей оказались: а) женская аудитория до 27 лет, работающие или живущие рядом, предпочитающие групповые занятия; б) мужская аудитория со средним возрастом 27 лет, которые работают неподалёку, посещают обычно спортивный клуб поздно вечером после работы; в) поклонники силовых тренировок, которые часто проводят в залах весь день.
4. Особенно важно было показать при разработке, что деятельность фитнес-центра организована на очень высоком профессиональном уровне. Все сотрудники высококвалифицированные, каждый тренер получил академическое образование по фитнесу.

***

## 3.2 Реализация информационной системы <a name="реализация"></a>

в процессе
***
## 4 Тестирование информационной системы <a name="тестирование"></a>

Тестируем сайт, проверяем адаптацию под мобильные устройства.

***

## Заключение <a name="заключение"></a>

если всё работать будет, то и итог будет...
***
## Список использованных источников <a name="ссылки"></a>

сайты, книги и пр..




