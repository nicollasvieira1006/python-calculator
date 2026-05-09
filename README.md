# Python Calculator 🧮

Calculadora desenvolvida em Python para prática de lógica de programação, estruturas condicionais e operações matemáticas.

---

## 🚀 Funcionalidades

* Soma
* Subtração
* Multiplicação
* Divisão
* Verificação de número PAR ou ÍMPAR
* Tratamento de divisão por zero

---

## 💻 Tecnologias utilizadas

* Python

---

## ▶️ Como executar

```python
print("================= CALCULADORA PYTHON =================")

# Entrada de dados
n1 = float(input("\nDigite o primeiro número: "))
n2 = float(input("Digite o segundo número: "))

# Escolha da operação
operacao = input(
    "\nEscolha a operação (+, -, *, /): "
)
print("=====================================================")
resultado = 0

# Operações
if operacao == "+":
    resultado = n1 + n2
    print(f"\nResultado da soma: {resultado}")

elif operacao == "-":
    resultado = n1 - n2
    print(f"\nResultado da subtração: {resultado}")

elif operacao == "*":
    resultado = n1 * n2
    print(f"\nResultado da multiplicação: {resultado}")

elif operacao == "/":

    if n2 != 0:
        resultado = n1 / n2
        print(f"\nResultado da divisão: {resultado}")

    else:
        print("\nErro: divisão por zero é inválida.")

else:
    print("\nOperação inválida.")

# Verificação PAR ou ÍMPAR
if operacao in ["+", "-", "*", "/"] and n2 != 0:

    if resultado % 2 == 0:
        print("O resultado é PAR.")

    else:
        print("O resultado é ÍMPAR.")
        
```
---

## 📚 Objetivo do projeto

Projeto criado para praticar lógica de programação e fundamentos da linguagem Python durante minha transição para Desenvolvimento de Software.
