7. Высококачественные методы
==============

### Контрольный список

#### Общие вопросы 

+ Достаточна ли причина создания метода? 
+ Все ли части метода, которые целесообразно поместить в отдельные методы, сделаны отдельными методами? 
+ Имеет  ли  имя  процедуры  вид  «выразительный  глагол + объект»?  Описывает  ли  имя  функции  возвращаемое  из нее  значение?
+ Описывает  ли  имя  метода  все  выполняемые  в  методе действия?
+ Задали  ли  вы  конвенции  именования  часто  выполняемых  операций?
+ Имеет  ли  метод  высокую  функциональную  связность?
Решает  ли  он  только  одну  задачу  и  хорошо  ли  он  с  ней  справляется?
+ Имеют  ли  методы  слабое  сопряжение?  Являются  ли  связи  метода  с  другими  методами  малочисленными,  детальными,  заметными  и  гибкими?
+ Обусловлена  ли  длина  метода  его  ролью  и  логикой,  а  не  искусственным стандартом  кодирования?

#### Передача  параметров

+ Формирует  ли  в  целом  список  параметров  метода  согласованную  абстракцию  интерфейса?
+ Разумно  ли  упорядочены  параметры  метода?  Соответствует  ли  их  порядок порядку  параметров  аналогичных  методов?
+ Документированы  ли  выраженные  в  интерфейсе  предположения?
+ Метод  имеет  семь  параметров  или  меньше?
+ Все  ли  входные  параметры  используются?
+ Все  ли  выходные  параметры  используются?
+ Не  используются  ли  входные  параметры  в  качестве  рабочих  переменных?
+ Если  метод  является  функцией,  возвращает  ли  он  корректное  значение  во всех  возможных  случаях?

### Ключевые моменты

+ Самая  важная,  но  далеко  не  единственная  причина  создания  методов  —  улучшение  интеллектуальной  управляемости  программы.  Сокращение  кода  —  не такая  уж  и  важная  причина;  повышение  его  удобочитаемости,  надежности  и облегчение  его  изменения  куда  важнее.
+ Иногда огромную выгоду можно извлечь, создав отдельный метод для простой операции.
+ Связность методов можно разделить на несколько видов. Самая лучшая — функциональная  —  достижима  практически  всегда.
+ Имя  метода  является  признаком  его  качества.  Плохое,  но  точное  имя  часто указывает  на  плохое  проектирование  метода.  Плохое  и  неточное  имя  не  описывает роль метода. Как бы то ни было, плохое имя предполагает, что программу нужно  изменить.
+ Функцию  следует  использовать,  только  когда  главной  целью  метода  является возврат  конкретного  значения,  описываемого  именем  функции.
+ Добросовестные программисты используют методы-макросы с осторожностью и  только  в  крайнем  случае.