# Python
Eu criei um programa em que o usuário coloca um **input** em duas **list** de 10 numeros inteiros, e após disso, as 'soma' com **join**.
~~~python
a = []
b = []
c = []

#Coloca os valores na lista 'a'

for i in range(10):
    d = int(input('Coloque um numero: '))
    a.append(d)
print(a) 

#Coloca os valores na lista 'b'

for i in range(10):
    d = int(input('Coloque um numero: '))
    b.append(d)
print(b) 

# Somando as duas listas

c = a + b
print(c)
~~~
---
