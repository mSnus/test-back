# Тестовое задание для бэкенд-программиста. #

## Требуемый стек: ##
PHP 7-8, Laravel, mySQL

### Краткое описание: ###
Имитируем поведение информационной системы - CRM.

### Задание подробно: ###

*В системе есть должны быть:*
- пользователи (имя, номер телефона, страна). 
	- количество пользователей: до 10000.
	
- шаблоны документов (тип документа, список полей) 
	- например: 
		- тип: паспорт, поля: номер, дата выдачи, кем выдан
		- тип: водительское удостоверение, поля: номер, дата выдачи
		- и т.п.
	- количество шаблонов: до 10.
	
- список стран (название, телефонный код страны) - 
	- например, Россия: +7. 
	- количество стран: до 1000

У пользователей в CRM может быть заполнено несколько документов.
Данные можно сгенерировать свои или взять готовые из приложенных CSV-файлов.

*Количества выше приведены только для удобства проектирования системы, 
генерировать их в таком количестве не требуется.*

### Ожидаемый результат: ###
Конечным результатом задания должна быть страница 
со списом пользователей, их телефонными номерами с кодом страны 
и со всеми их заполненными документами.

Результат необходимо предоставить в виде php-приложения, запускаемого через artisan serve,
базу данных - в виде дампа mysql, имя БД используйте **clearield_test**.
