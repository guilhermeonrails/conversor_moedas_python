# Conversor de moedas em Python

Criando o projeto inspirado na primeira aula da Imersão dev feito em JS. 

- Código em JS

```
var valorEmDolarTexto = prompt("Qual o valor em dolar que você quer converter?")
var valorEmDolarNumero = parseFloat(valorEmDolarTexto)
var valorEmReal = valorEmDolarNumero * 5.51
var valorEmRealFixado = valorEmReal.toFixed(2)
alert(valorEmRealFixado)
```

- Código em Python

```
valor_em_dolar_texto = input('Digite o valor em dolar')
valor_em_dolar_numerico = float(valor_em_dolar_texto)
valor_em_real = valor_em_dolar_numerico * 5.51
valor_em_real_fixado = round(valor_em_real,2)
valor_em_real_fixado
```
