# Поток событий
---

![UseCase](https://github.com/ALPause23/Trtpo_Route_guide/blob/master/Documentation/Diagrams/UseCase/Use%20Case%20Diagram.jpg)

# Содержание
1 [Актёры](#1) <br>
2 [Варианты использования](#2) <br>
2.1 [Вход в приложение](#2.1) <br>
2.2 [Поиск маршрута](#2.2) <br>
2.3 [Выведение списков маршрутов](#2.3) <br>
2.4 [Вывод данных об приложении](#2.4) <br>
2.5 [Выбор типа транспорта для необходимых маршрутов](#2.5) <br>
2.6 [Выбор типа транспорта для списка маршрутов](#2.6) <br>
2.7 [Установка даты](#2.7) <br>
2.8 [Установка места прибытия/отправления](#2.8) <br>
<a name="1"/>

# 1 Актёры

Человек, желающий пользоватся данным приложением.

<a name="2"/>

# 2 Варианты использования

<a name="2.1"/>

## 2.1 Вход в приложение

**Описание.** Вариант использования "Вход в приложение" позволяет пользователю войти в приложения "Route quite".  

**Основной поток.**
1. Вариант использования начинается, когда пользователь запускает приложение;
2. Приложение предлагает ввести иммя пользователя и узнать наличие Интернет-соединения;
3. Пользователь нажимает кнопку "Вход";
4. Приложение проверяет введенные данные. Если выбрана клавиша "Нет", то появляется уведомление об проблеме в работе с приложением;
7. Приложение открывает главное окно;
8. Вариант использования завершается;

<a name="2.2"/>

## 2.2 Поиск маршрута

**Описание.** Вариант использования "Поиск маршрута" позволяет пользователю произвести поиск маршрута, в зависимости от параметров фильтра.  

**Основной поток.**
1. Пользователь выбирает вкладку "Поиск маршрута";
2. Пользователь выбирает тип транспорта;
3. Пользователь заполняет данные для фильтра маршрутов;
4. Пользователь нажимает кнопку "Поиск";
5. Приложение выводит список маршрутов на экран в таблицу;
6. Вариант использования завершается;

<a name="2.3"/>

## 2.3 Выведение списков маршрутов

**Описание.** Вариант использования "Выведение списков маршрутов" позволяет пользователю вывести на экран список всех марштутов, в завасимости от необходимого типа транспорта.

**Основной поток.**
1. Пользователь выбирает вкладку "Список маршрутов";
2. Пользователь выбирает тип транспорта;
3. Приложение выводит список маршрутов на экран в таблицу;
4. Вариант использования завершается;

<a name="2.4"/>

## 2.4 Вывод данных об приложении

**Описание.** Вариант использования "Вывод данных об приложении" позволяет просмотреть информацию о данном приложении.  

**Основной поток.**
1. Пользователь нажимает кнопку "About";
2. Приложение окно с информацией об приложении;
3. Вариант использования завершается;

<a name="2.5"/>

## 2.5 Выбор типа транспорта для необходимых маршрутов

**Описание.** Вариант использования "Выбор типа транспорта для необходимых маршрутов" позволяет выбрать тип необходимого транспорта.  
**Предусловие.** Пользователь выбрал вкладку "Поиск маршрутов" в главном окне.

**Основной поток.**
1. Пользователь нажимает на на ComboBox "Тип транспорта";
2. Пользователь установливает тип транспорта;
3. Пользователь нажимает кнопку "Поиск";
4. Приложение вносит изменения;
5. Вариант использования завершается;

<a name="2.6"/>

## 2.6 Выбор типа транспорта для списка маршрутов

**Описание.** Вариант использования "Выбор типа транспорта для списка маршрутов" позволяет выбрать ти необходимого транспорта.
**Предусловие.** Пользователь выбрал вкладку "Список маршрутов" в главном окне.

**Основной поток.**
1. Пользователь нажимает на на ComboBox "Тип транспорта";
2. Пользователь установливает тип транспорта;
3. Пользователь нажимает кнопку "Поиск";
4. Приложение вносит изменения;
5. Вариант использования завершается;

<a name="2.7"/>

## 2.7 Установка даты

**Описание.** Вариант использования "Установка даты" позволяет пользователю установить дату отправления.

**Основной поток.**
1. Пользователь устанавливает дату в поле "Дата";
2. Пользователь нажимает кнопку "Поиск";
3. Приложение изменяет дату;
4. Вариант использования завершается.

<a name="2.8"/>

## 2.8 Выбор оповещений

**Описание.** Вариант использования "Установка места прибытия/отправления" позволяет установить место отправления и место прибытия.

**Основной поток.**
1. Пользователь устанавливает места прибытия в поле "Место прибытия";
2. Пользователь устанавливает места прибытия в поле "Место отправления";
3. Пользователь нажимает кнопку "Поиск";
4. Приложение изменяет дату;
5. Вариант использования завершается.
