# python-code-
a beginner project in python
nota1 = float(input('coloque a sua primeira nota:'))
nota2 = float(input('coloque a segunda nota'))


while nota1 < 0 or nota1 > 10:
    nota1 = float(input(' primeira nota invalida, coloque a nota novamente'))

while nota2 < 0 or nota2 > 10:
    nota2 = float(input(' segunda nota invalida, coloque a nota novamente'))


total = nota1 + nota2
media = total / 2


if media >= 6.0:
    print(f' a sua media foi de {media} e voce passou nesse trimestre')
else:
    print(f'a sua media foi de {media} e voce nao passou nesse trismtre')
