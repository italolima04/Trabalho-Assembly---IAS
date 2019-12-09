# Trabalho-Assembly---IAS
Trabalho de resolução de questões em Assembly, utilizando o Conjunto de Instruções do IAS.
Lista de Exercícios com questões que devem atender as seguintes prescrições:

1-Faça um programa que recebe dois valores inteiros nos endereços de memória 0x100 e
0x101 e armazena a soma deles no endereço 0x110 e a subtração no endereço 111.
2-Escreva um programa que calcula a seguinte expressão: A = (A + B) - (C + D). Em
quais endereços de memória estão as variáveis?
3-Escreva um programa que calcula a seguinte expressão: A = (A + B) * (C + D). Em
quais endereços de memória estão as variáveis?
4-Escreva um programa que calcula a seguinte expressão: A = (A + B) / (C + D). Em
quais endereços de memória estão as variáveis?
5-Faça um programa que recebe 3 notas e 3 pesos, calcule e salve a média ponderada
dessas notas no endereço 0x100.
6-Faça um programa que recebe dois inteiro x e b e imprime a soma, subtração, divisão e
o resto da divisão entre x e b. Especifique as posições de memória de todas as variáveis
usadas.
7-Faça um programa que receba, nos endereços de memória especificados, o salário de
um funcionário 0x100 e o percentual de aumento 0x101, calcule e mostre o valor do
aumento 0x102 e o valor do novo salário 0x103.
8-Faça um programa que leia o valor da base e altura de um triângulo e calcule o valor
da sua área. Especifique as posições de memória de todas as variáveis usadas.
9-Faça um programa que, dado o raio de um disco na memória 0x100, guarda no endereço
de memória 0x101 e 0x102 sua área e seu perı́metro, respectivamente.
10-Escreva um procedimento que recebe dois números inteiros, nos endereços de memória
0x100 e 0x101, e determina se eles são ou não coprimos, escrevendo no endereço de
memória 102 um se eles forem coprimos e zero caso contrário. Dois números a e b são
coprimos se não há um divisor d > 1 que seja comum a ambos. Por exemplo, 15 e 8
são coprimos pois os divisores de 8, que são 2, 4 e 8, não são divisores de 15.
11-Escreva uma procedimento que recebe um vetor de inteiros, no endereço de memória
0x102, e seu tamanho, no endereço de memória 0x100, e um valor inteiro n no endereço
de memória 0x101. Faça um programa que atualiza cada elemento do vetor pela soma
do elemento com n.
12-Escreva um procedimento para calcular o fatorial de um número n. Especifique as
posições de memória de todas as variáveis usadas.
13-Faça um programa que lê dois números inteiros positivos a e b e calcula a ∗ b usando
apenas somas. Especifique as posições de memória de todas as variáveis usadas.
14-Escreva um programa em linguagem de montagem IAS para calcular o produto escalar
de dois vetores. Produto escalar é uma operação que realiza a soma dos produtos de
todos os elementos de 2 vetores, dois a dois. Por exemplo, para os vetores A=(1,2)
e B=(4,13), temos o seguinte produto escalar: 1*4+2*13 = 30. Você pode supor
que os vetores possuem o mesmo tamanho, contudo esse tamanho é arbitrário. Os
vetores podem ou não estar representados consecutivamente no mapa de memória.
Mais informações são apresentadas na seção abaixo.
• O tamanho dos vetores deve ser lido da memória, no endereço 0x5FF;
• Os vetores possuem pelo menos um elemento;
• Os endereços dos vetores (endereços do primeiro elemento de cada vetor) devem
ser lidos da memória (endereços 0x3FD e 0x3FE);
• Seu programa deve organizar o mapa de memória em 3 partes:
– Na primeira parte há o código (instruções) e dados;
– Na segunda parte (o “meio” do mapa de memória) estão os 2 vetores;
– Nas 3 últimas posições estão armazenados os endereços iniciais e o tamanho
dos vetores, conforme explicado no item acima.
• Termine a execução com um salto para o endereço 0x400;
• Antes de terminar a execução, salve o resultado do produto escalar no registrador
AC.
