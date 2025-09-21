<p align="center">
  <img src="calculator.png" width="100" alt="Calculator Icon"/>
</p>

<h1 align="center"> Calculadora</h1>

<p align="center">
  Uma calculadora moderna e extensível para o terminal, feita com Python.
</p>

<p align="center">
  <a href="https://github.com/nandahelena/calculadora/actions/workflows/blank.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/nandahelena/calculadora/blank.yml?branch=main&label=CI&logo=github&style=flat-square" alt="CI Status"/>
  </a>

  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/python-3.10%2B-blue?style=flat-square&logo=python" alt="Python version"/>
  </a>

  <a href="https://github.com/nandahelena/calculadora/commits/main">
    <img src="https://img.shields.io/github/last-commit/nandahelena/calculadora/main?style=flat-square" alt="Last Commit"/>
  </a>

<a href="https://pypi.org/project/calculadora/">
  <img src="https://img.shields.io/pypi/dm/calculadora?style=flat-square" alt="PyPI downloads"/>
</a>
</p>

---

## Sobre

A **Calculadora** é uma biblioteca Python para realizar cálculos diretamente no terminal, com uma API simples e poderosa. Suporta desde operações básicas até funções científicas e expressões complexas.

---

## Instalação

Instale via pip:


```
pip install calculadora
```

Ou clone o repositório:
```
git clone https://github.com/seuusuario/calculadora.git
cd calculadora
pip install -e .
```

# Funcionalidades
- Operações básicas: +, -, *, /
- Funções científicas: sin, cos, tan, log, sqrt
- Avaliação de expressões: "2 + 3 * (4 - 1)"
- Precisão com números decimais
- API extensível para novos operadores
- Suporte a temas e cores no terminal (via Rich)

# Exemplo de uso
```
from calculadora import Calc

calc = Calc()
print(calc.avaliar("2 + 2 * 3"))  # Saída: 8
print(calc.sqrt(16))              # Saída: 4.0
print(calc.seno(90))              # Saída: 1.0
```

# Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
