nome = input("Digite seu nome: ")
idade = int(input("Digite sua idade: "))

if idade < 0:
    print("recém-nascido!")
elif idade < 5:
    print(nome, "é criança")
elif idade < 15:
    print(nome, "é pré-adolescente")
elif idade < 18:
    print(nome, "é adolescente")
elif idade < 60:
    print(nome, "é adulto")
else:
    print(nome, "é idoso")
    
