# LowercaseToUppercaseBrainfuck
Linguagem: Brainfuck

Observações: Não há tratamento para quando o usuário coloca um caracter que não seja uma letra minúscula.


Brainfuck

Na linguagem Brainfuck qualquer caractere não "> <+ -., []" (Excluindo aspas) é ignorado.


Brainfuck é representado por uma matriz com 30.000 células inicializadas a zero
e um ponteiro de dados apontando para a célula atual.


Existem oito comandos:

+ : Incrementa o valor na célula atual por um.

- : Decrementa o valor na célula atual por um.

> : Move o ponteiro de dados para a próxima célula (célula à direita).

< : Move o ponteiro de dados para a célula anterior (célula à esquerda).

. : Imprime o valor ASCII na célula atual (ou seja, 65 = 'A').

, : Lê um único caractere de entrada na célula atual.

[ : Se o valor na célula atual é zero, ignora o correspondente ].

     Caso contrário, avance para a próxima instrução.
     
] : Se o valor na célula atual for zero, mude para a próxima instrução.

     Caso contrário, mova para trás nas instruções para o correspondente [.
     

[e] formam um loop while. Obviamente, eles devem ser equilibrados.

Fonte: Learn X in Y minutes
