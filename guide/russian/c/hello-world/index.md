---
title: Hello World C
localeTitle: Привет, мир C
---
\## Привет, мир

Для записи на консоль вы можете использовать функцию `printf()` содержащуюся в библиотеке, `include <stdio.h>`

\`\` \`C #включают

int main (void) {
```
 printf("hello, world\n");  //lines starting with this are called comments.. 
 
 return 0; 
```

} \`\` \` ## Объяснение

*   #Include является командой препроцессора. Эта команда сообщает компилятору включить содержимое файла stdio.h (стандартный ввод и вывод) в программу.
    
*   Файл stdio.h содержит такие функции, как scanf () и print () для ввода ввода и вывода вывода соответственно.
    
*   Если вы используете функцию printf (), не записывая #include , программа не будет компилироваться.
    
*   Выполнение программы C начинается с функции main ().
    
*   Функция printf () представляет собой библиотечную функцию для отправки форматированного вывода на экран. В этой программе printf () отображает Hello, World! текст на экране.
    
*   Возврат 0; statement - это «статус выхода» программы. Проще говоря, программа заканчивается этим утверждением
    
    ## Вывод:
    
    \`\` \`
    

> Привет мир \`\` \`