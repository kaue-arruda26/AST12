# Respostas AST12 - Parte 2

## 1. Qual foi a mensagem exata de erro que o Pytest imprimiu?
`AssertionError: assert {'resultado': 2} == {'resultado': 8}`

## 2. O que ele esperava receber e o que ele recebeu de fato?
O Pytest esperava receber `{"resultado": 8}` (referente ? soma de 5 + 3), mas recebeu de fato `{"resultado": 2}` (devido ? altera??o na fun??o no `main.py` para subtrair 5 - 3).
