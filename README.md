# python_tipagem_dinamica

"Python é uma linguagem de tipagem dinâmica e forte. Isso significa que o tipo de uma variável é determinado em tempo de execução, baseado no valor que lhe é atribuído (um conceito conhecido como duck typing). No entanto, o Python impõe restrições fortes sobre as operações que podem ser realizadas com cada tipo de dado.

A tipagem dinâmica confere flexibilidade ao Python, permitindo que você não precise declarar explicitamente o tipo de uma variável. Por outro lado, a tipagem forte garante a segurança do código, evitando erros comuns causados por operações inválidas entre tipos incompatíveis.

Em resumo:

Tipagem dinâmica: O tipo da variável é definido em tempo de execução.
Tipagem forte: O Python verifica se as operações são válidas para os tipos envolvidos.
Exemplo:

```
Python
nome = "João"  # Variável do tipo string
idade = 30     # Variável do tipo inteiro

# Operação válida:
print("Olá, " + nome + "! Você tem " + str(idade) + " anos.")

# Operação inválida (sem conversão):
# print(nome + idade)  # Geraria um erro
```
