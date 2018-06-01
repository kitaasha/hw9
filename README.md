# hw9
Я использовала программу Notepad++
------------------------------------
1. Удалить все пустые строки
* Использовала регулярное выражение \n\r, которое заменила на \0, и удалила все пустые строки
![](https://github.com/kitaasha/hw9/blob/master/3.png)
* Использовала регулярное выражение [\s]*$, которое заменила на \0, чтобы убрать пробелы в начале строк
![](https://github.com/kitaasha/hw9/blob/master/4.png)
----------------------------------------
2.Найти всех князей и города, имя и название которых оканчивается на "слав". В выдаче должны быть такие слова как "Ярославля, Ростиславъ, Ростиславу, Переяславлъ" и т.п. Но не должно быть "славу, выславше" и т.п. 
* Использовала регулярное выражение [А-Я]+\w+слав+\w*. Итог- 592 вхождения
![](https://github.com/kitaasha/hw9/blob/master/1.png)
-------------------------------------
3.Найти все упоминания Новгорода. Учтите, что написание может быть разным . В выдаче должны быть такие слова как "Новѣгородѣ, Новъгородъ, Новгородцю, Новагорода, Новугороду". 
* Использовала регулярное выражение (Новѣ?город[а-я]?|Новъ?город[а-я]?|Новгородц[а-я]?|Новагород[а-я]?|Новугород[а-я]?|Новгород[а-я]?). Итог- 59 вхождений
![](https://github.com/kitaasha/hw9/blob/master/2.png)
