# calculadora-edo

## Calculadora de Equações Diferenciais (EDO)
Este é um script em Python desenvolvido para resolver equações diferenciais ordinárias (EDOs) de primeira e segunda ordem. O projeto foi realizado em grupo, como parte de uma atividade proposta em sala de aula, utilizando alguns exemplos de equações.

Sobre o Projeto
Este script permite resolver EDOs de primeira e segunda ordem, fornecendo uma maneira interativa para os usuários inserirem os coeficientes e as funções envolvidas. A aplicação foi inicialmente idealizada para ser uma aplicação web, mas nesta versão apenas um script Python foi desenvolvido.

Exemplos de Equações
Equações de 1ª Ordem
Forma geral: A * dy/dx + B * y = C

Exemplo 1:
Coeficientes: A = 2, B = 3
C (Função F(x)): euler^x + 0
Exemplo 2:
Coeficientes: A = 1, B = -1
C (Função F(x)): x**2
Equações de 2ª Ordem
Forma geral: A * d²y/dx² + B * dy/dx + C * y = D

Exemplo 1:

Coeficientes: A = 1, B = 2, C = 1
D (Função F(x)): euler^(2*x) + 0
Exemplo 2:

Coeficientes: A = 1, B = -3, C = 2
D (Função F(x)): sin(x)
Principais Operadores Utilizados
+: Adição
-: Subtração
*: Multiplicação
/: Divisão
**: Potenciação
Como Executar
Para executar o script, basta ter Python instalado e rodar o arquivo Calculadora_EDO.py. Você será guiado por perguntas interativas para definir os coeficientes e resolver a equação desejada.

Requisitos
Python 3.x
