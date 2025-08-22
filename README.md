# macaquinho_da_computacao
criar códigos para minha evolução no curso de desenvolvimento de sistemas

Participantes = int(input("Quantas pessoas entraram? "))
Reuniao = str(input("Qual o seu tipo de reunião? (normal ou executiva) "))

if Participantes <= 5:
    if Reuniao == "normal":
        sala = ("vá para a sala normal")
    else:
        sala = ("vá para a sala executiva")

elif Participantes <= 14:
    if Reuniao == "normal":
        sala = ("vá para a sala média")
    else:
        sala = ("vá para a sala executiva")
        
elif Participantes >= 15:
    if Reuniao == "executiva":
        sala = ("bem-vindo a sala executiva")
    else:
        sala = ("agende um dia para utilizar a sala executiva")
else:
    sala = ("quantidade inválida")
    
print (sala)
