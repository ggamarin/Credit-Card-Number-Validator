# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

15.02.2020 было проведено тестирование по установке приложения Credit Card Number Validator и его работе.

На тестирование затрачено: 1 час.

##  Процесс тестирования
 ### Что тестировалось
  * Руководство по установке IntelliJ IDEA
  * Проверка работы программы
  * Запуск программы с разными тестовыми данными
  
В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* Тест-план и данные, описанные в [легенде](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0-1)
* Тест-сьют, состоящий из :
   * проверки валидных номеров карт
   * проверки невалидных номеров карт
 * Данный отчет о тестировании

В качестве тестовых данных использовались данные [1](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md), [2](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0-1), [3](https://www.freeformatter.com/credit-card-number-generator-validator.html):
### Тестирование установки IntelliJ IDEA
 1. Зайти по [ссылке](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
 2. Выполнить шаги перечисленные в инструкции
**Ожидаемый результат:** Программа запускается, запускает предоставленный код с сообщением "Hello programming!"
 
  **Фактический результат:** Программа запускается, запускает предоставленный код с сообщением "Hello programming!"
### Проверка работы IntelliJ IDEA
1. Запустить программу
2. Заменить код с "Hello programming!" целиком на тот, что приведён в [легенде](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0-1)
3. Запустить код.

**Ожидаемый результат:** Код выполняется и выводит сообщение Result is OK

**Фактический результат** Код выполняется и выводит сообщение Result is OK
https://imgur.com/FFMLewh
### Проверка работы программы с разными тестовыми данными
1. Запустить IntelliJ IDEA
2. Поменять номер в 4ой строке кода(например, взяв номер [отсюда](https://www.freeformatter.com/credit-card-number-generator-validator.html))
3. Запустить код

**Ожидаемый результат:** Код запускается и выдает сообщение Result is OK при валидном номере, Result is FAIL при невалидном.

https://imgur.com/9mG8r31

https://imgur.com/fg09WQZ

Тестирование производилось в следующем окружении:
* Windows 10, 64 bit
* Java11
* IntelliJ IDEA Community 2019.3.3

