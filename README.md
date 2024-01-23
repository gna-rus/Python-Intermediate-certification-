# Промежуточная атестационная работа
### Task1 from 12 Seminar
В Task1 from 12 Seminar брался за основу код из Д\з Задачки 1 "Урок 12. ООП. Финал". По условию задачи требуется реализовать систему сохранения информации об оценках по разным предметам у студента (в рамках кода реализовал только Математику и Историю), выводить информацию о среднем бале по тестам и учебе студента


В программе реализована система ввода из строки терминала. Пример ввода:

**python file.py -ln Ivanov -fn Ivan -mc 4 -mt 89 -hc 3 -ht 76 -fc 2**

- file.py - название файла
* -ln - Введите фамилию
* -fn - Введите имя
* -dn - Введите название файла для сохранения
* -mc - Введите оценку для студента за урок по математике
* -hc - Введите оценку для студента за урок по истории
* -mt - Введите оценку для студента за тест по математике
* -ht - Введите оценку для студента за тест по истории
* -fc - Введите 1 или 2. Если введи 1 то программа добавит иформацию о студенте (добавит в файл информацию о оценках). Если ввести 2 то программа выведит средний балл у студента

Информация о студенте сохраняется в файл **class.json** и средний бал вычисляется из информации хранящейся в нем.
  
Логгирование реализовано и информация сохраняется в файл **project.log**


### Task3 from 13 Seminar
В Task3 from 13 Seminar за основу обралась задачка №3 из 13 семинара. По условию задачки необходимо написать код, который будет создавать обьекты, в которые будут передаваться информация о ФИО сотрудника, его возраст и его ID. Должна быть реализована система смены возраста из-за дня рождения и определение уровня сотрудника по его ID. Информация сохраняется только через логгирование.

В программе реализована система ввода из строки терминала. Пример ввода:

**python file.py -ln Ivanov -fn Ivan -pt Ivaovoch -a 30 -id 12345**

Логгирование реализовано и информация сохраняется в файл **project.log**

### Task6 from 15 Seminar
Эта задачка, которую не успели сделать на семинаре. Так как условие задачки не содержит много текста, для удовбства было продублировано и закоментировано это задание с сам код.

Программа принимает адрес дирректории и обрабатывает информацию о папках и файлах находящиеся в ней.

**Важно!** Все вложения обрабатываются рекурсивным методом, не рекомендуется передавать дирректроию, в которой содержится большое количество файлов и папок. Также не рекомендуется передвать дирректорию в которой наименования каждй оотдеьной папки содержит больше одного слова.

Информация сохраняется в формате **namedtuple**. 

В программе реализована система ввода из строки терминала. Пример ввода:

**python file.py -ln D:\python\Git**

Логгирование реализовано и информация сохраняется в файл **project.log**
