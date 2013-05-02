printf
=
Задача — вывести строку, содержащую отформатированное согласно флагам
десятичное число.
Программа запускается с двумя аргументами — форматная строка и само число.
Форматная строка имеет вид: [флаги][длина].
Форматирование происходит как и у printf:

* Флаги
  * ' '
  * '+'
  * '-'
  * '0'

Значение длины — от 1 до 50. Может быть не указано, в этом случае считаем её
равной единице. 

Число — строка, содержащая шестнадцатеричное представление 128-битного числа
(то есть максимум может быть 32 цифры). Если в строке меньше 32 цифр, значит,
в недостающих цифрах — нули. Число в дополнительном коде. В строке перед числом
может стоять минус, который меняет знак числа.

//Когда-нибудь я это перепишу