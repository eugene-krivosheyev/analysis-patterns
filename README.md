Analysis Patterns
=================
24 hrs

Agenda
======

Введение
--------
- [ ] Знакомство с участниками и сбор проблем
- [ ] Обзор тренинга
- [ ] Разбивка участников по командам

Концептуальное моделирование
----------------------------
- [ ] Что такое аналитическая/концептуальная модель предметной области?
- [ ] В чем ценность аналитической/концептуальной модели предметной области?
- Влияние аналитической модели на качество через снятие рисков (-> DDD)
- Влияние аналитической модели на границы системы
- Влияние аналитической модели на точки расширения системы
- Влияние аналитической модели на дизайн (-> DDD)
- [ ] Идея «точек зрения» (PoV): сценарии + концептуальная модель
- [ ] Что на выходе концептульного моделирования?
- Для кого мы делаем концептуальную модель?
- Каковы критерии полноты модели?
- [ ] Способы документирования концептуальной модели
- Неформализованный текст: глоссарий
- Формализованный текст: CRC-карточки
- Графическая нотация: UML, ERD, ArhiMate

Самостоятельное моделирование
-----------------------------
- [ ] Дана история
```
Я, как зарегистрированный пользователь, хочу посмотреть каталог товаров, чтобы выбрать товар для покупки
```
- [ ] Когда команды описывают концептуальную модель в виде глоссария
- [ ] Тогда на разборе проводится ревью
- на полноту
- на понятность

Использование UML для концептуального моделирования
---------------------------------------------------
- [ ] Идея «точек зрения» (PoV): статика + динамика
- [ ] Моделирование 
- Моделирование статики: концептов и связей
- Моделирование ограничений: мощность связей, OCL-выражения, комментарии
- Моделирование динамики: объектов и сигналов

Самостоятельное моделирование
-----------------------------
- [ ] Дана та же история
- [ ] Когда команды описывают концептуальную модель на UML
- [ ] Тогда на разборе проводится ревью
- на полноту
- на понятность

Введение в приемы объектно-ориентированного анализа предметной области
----------------------------------------------------------------------
- [ ] Каковы критерии полноты модели?
- [ ] Как мы выделяем концепты?
- [ ] Базовые техники дополнения аналитической модели и сценариев:
- докомпозиция историй по сценариям (с граничными условиями)
- свойства концептов (прилагательные) и их жизненный цикл
- характер связей между концептами
- замыкание операций над концептами до CRUD
- акторы сценариев
- количество объектов
- сохраняемость объектов
- {BRs}
- [ ] [Аналитические паттерны](https://www.dropbox.com/sh/fovo9utg47xoswn/AAD8trpO7RitUSECBRJXdJVMa!?dl=0)

Самостоятельное моделирование
-----------------------------
- [ ] Дана та же история
- [ ] Когда команды 
- дополняют истории и их сценарии
- доописывают концептуальную модель на UML
- [ ] Тогда на разборе проводится ревью
- на полноту
- на понятность

Паттерны идентификации объектов в сложном мире
----------------------------------------------
- [ ] Name
- [ ] Identification Scheme
- [ ] Object Merge
- [ ] Object Equivalencе

[Паттерны моделирования изменяемых во времени концептов](https://martinfowler.com/eaaDev/)
------------------------------------------------------
- [ ] [Timepoint](https://martinfowler.com/eaaDev/TimePoint.html)
- [ ] [Audit Log](https://martinfowler.com/eaaDev/AuditLog.html)
- [ ] [Temporary Field and Temporary Object](https://martinfowler.com/eaaDev/TemporalProperty.html)
- [ ] [Snapshot](https://martinfowler.com/eaaDev/Snapshot.html)
- [ ] [Effectivity](https://martinfowler.com/eaaDev/Effectivity.html)

[Идиомы ОО-анализа](https://www.google.com/url?q=https://www.dropbox.com/s/rs9linv967xk6s1/%255BSkillTrek%255D%2520Type%2520Idioms%2520at%2520Domain%2520Analysis.pdf?dl%3D0&sa=D&source=docs&ust=1670213951634577&usg=AOvVaw3HpP-uBeqAubjbn5Yr30OS)
-----------------
- [ ] Динамическая типизация объекта
- [ ] Типизация связи
- [ ] Динамическая типизация связи
- [ ] Мета-уровень

Паттерны моделирования структуры компании
-----------------------------------------
- [ ] Party
- [ ] Organization Hierarchies
- [ ] Organization Structure
- [ ] Accountability
- [ ] Accountability Knowledge Level

Паттерны моделирования хранения и учета*
---------------------------------------
- [ ] Account
- [ ] Transactions
- [ ] Multilegged Transactions
- [ ] Summary and Memo Accounts
- [ ] Posting Rules
- [ ] Entries
- [ ] Balance Sheet and Income Statement
- [ ] Corresponding Account
- [ ] Specialized Account Model
- [ ] Booking Entries to Multiple Accounts

Финальная ретроспектива
-----------------------
- [ ] Training improvements
- [ ] Takeaways
- [ ] Action plan
