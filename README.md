# ResolucaoExercicio2.13Deitel

**Resolução do Exercício 2.13 Deitel**

**2.13 Declare a ordem de avaliação dos operadores em cada uma das seguintes instruções Java e mostre o valor de x depois que cada instrução é realizada:**<br><br>
**a) x = 7 + 3 \* 6 / 2 - 1;**<br>
x = (7 + (((3 \* 6) / 2 ) - 2));<br>
x = (7 + (((18) / 2) - 2));<br>
x = (7 + ((18 / 2) - 2));<br>
x = (7 + ((9) - 2)); <br>
x = (7 + (9 - 2));<br>
x = 7 + 7;<br>
x = 14; <br><br>

**b) x = 2 % 2 + 2 \* 2 - 2 / 2;**<br>
x = (((2 % 2) + (2 \* 2)) - (2 / 2));<br>
x = ((0) + (4) - (1));<br>
x = 3; <br><br>

**c) x = (3 \* 9 \* (3 + (9 \* 3 / (3))));**
x = (27 \* (3 + (27 / 3)));<br>
x = (27 \* (3 + (9)));<br>
x = (27 \* (12));<br>
x = 324<br><br>
