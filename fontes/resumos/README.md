#  Resumos de Python para Iniciantes

Este documento contém os principais conceitos aprendidos durante o estudo da linguagem Python, com exemplos práticos.

---

##  Introdução ao Python

Python é uma linguagem de programação simples, fácil de aprender e muito utilizada no mercado.

Principais usos:
- Automação de tarefas
- Desenvolvimento de sistemas
- Análise de dados

---

##  Variáveis

Variáveis são espaços na memória usados para armazenar informações.

Exemplo:

    nome = "Luciano"
    idade = 43

Explicação:
- "nome" guarda um texto
- "idade" guarda um número

---

##  Tipos de Dados

Principais tipos em Python:

- Texto (str)
- Número inteiro (int)
- Número decimal (float)
- Verdadeiro/Falso (bool)

Exemplo:

    nome = "João"       # texto
    idade = 30         # inteiro
    altura = 1.75      # decimal
    ativo = True       # booleano

---

##  Estruturas Condicionais (if/else)

Permitem tomar decisões no código.

Exemplo:

    idade = 18

    if idade >= 18:
        print("Maior de idade")
    else:
        print("Menor de idade")

---

##  Estruturas de Repetição (for)

Usadas para repetir ações.

Exemplo:

    for i in range(5):
        print(i)

Resultado:
0, 1, 2, 3, 4

---

##  Funções

Funções são blocos de código reutilizáveis.

Exemplo:

    def saudacao():
        print("Olá, tudo bem?")

    saudacao()

---

##  Aplicação prática (logística)

Exemplo simples de cálculo de frete:

    distancia = 100
    custo_por_km = 2.5

    frete = distancia * custo_por_km

    print("Valor do frete:", frete)

Explicação:
Multiplica a distância pelo custo por km para calcular o valor do frete.

---

##  Conclusão

- Python é fácil de aprender
- Permite automatizar tarefas
- Pode ser aplicado em diversas áreas, inclusive logística
