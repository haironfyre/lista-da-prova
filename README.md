#LISTA PARA A PROVA#

#QUESTÃO 1a
def main(a,b):
    soma = a + b
    return print("A soma de a + b eh igual a", soma)

main(4,5)

##QUESTÃO 1b
def divide(a,b):
    if b==0:
        return None
    else:
        r = a/b
        return print('', r)
divide(8,4)

##QUESTÃO 1f
def potencia(a,b):
    pot = a**b
    return print('', pot)
potencia(5,5)

#QUESTÃO 2
x=8
if x>=8.5:
    print("A")
if x>=7.5:
    print("B")
if x>=5.5:
    print("C")
if x>=5:
    print("D")

#QUESTÃO 3
x=8
if x>=8.5:
    print("A")
elif x>=7.5:
    print("B")
elif x>=5.5:
    print("C")
elif x>=5:
    print("D")

#QUESTÃO 4
x = 8
y = 5
z = 13
if x>=1 and x<=31:
    if y>0 and y<13:
        if (x+y)!=z:
            print("A data de hoje é 8/5/2018")
        else:
            print("A dara de hoje não é 8/5/13")
            
#QUESTÃO 5
num = ('40', '79', '45', '120', '5', '177', '241', '8999')

print(max(int(num) for num in num))

#QUESTÃO 6
def spam(n):
    for x in range(n):
        print("spam")
spam(15)

#QUESTÃO 7
def spam2(n):
    r = 1
    while r<=n:
        r = r+2
        if r > n:
            break
        else:
            print("spam")
spam2(20)

#QUESTÃO 8
def seq_imp(n):
    print(1)
    r = 1
    while r<n:
        r = r+2
        if r > n:
            break
        else:
            print(r)
seq_imp(100)
