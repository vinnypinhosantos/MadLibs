# MadLibs Com Python 
**Mad Libs** é um jogo de palavras modelo frasal criado por Leonard Stern e Roger Price. Consiste em um jogador solicitar aos outros uma lista de palavras para substituir os espaços em branco em uma história antes de ler em voz alta. O jogo é freqüentemente jogado como um jogo de festa ou como um passatempo.
## Conceitos de Python
Nesse mini-projeto coloquei em prática a interpolação de Strings.
Interpolar strings significa juntar texto com variáveis criadas.
Existem três de formas de fazer isso em Python:
### Concatenação de String
Concatenar é o jeito mais simples e comum à várias linguagens.
O sinal de "+" faz o trabalho de separar o texto da variável.
```python
nome = "Vinicius"
print("Meu nome é " + nome + ".")
```
### Format
Era o padrão e boa prática até algumas versões atrás.
O format é uma função que recebe como parâmetro a variável a ser interpolada na string.
As chaves representam o espaço para a váriavel.
```python
nome = "Vinicius"
print("Meu nome é {}.".format(nome))
```
### F-strings
A partir da versão 3.6 do Python, foram introduzidas as f-strings e se tornou boa prática a sua utilização.
É uma forma bem mais simples e com classe de fazer a interpolação.
```python
nome = "Vinicius"
print(f"Meu nome é {nome}")
```
## O Projeto
O projeto é bem simples: o usuário será perguntado por algumas palavras e no final será gerada uma história colocando essas palavras no contexto criado com a utilização de f-strings.

## Referência
<https://www.youtube.com/watch?v=8ext9G7xspg&t=287s>
