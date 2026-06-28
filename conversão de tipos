import os
def apresentação(): #bloco 1
    print("""Oque voce quer converter nessa porra?: 
         [1] celcius --> fahrenheit
         [2] kg --> gramas
         [3] litros --> ml """) #bloco 2 (dentro do 1)

def limpar_terminal(): #bloco 3
    if os.name == "nt": #bloco 4 (dentro do 3)
        os.system("cls") #bloco 5 (dentro do 4)


apresentação()

while True: #bloco 6
    
    try: #bloco 7 (dentro do 6)
        escolha1 = float(input("")) #bloco 8 (dentro do 7)
        if escolha1 not in (1,2,3): #bloco 9
            limpar_terminal()
            apresentação()
            print("\nAlguma das opcoes de Número acima, tente novamente: ")
            continue
            
        elif escolha1 == 1: #bloco 10
            celcius = float(input("Quanto quer converter para fahrenheit?: "))
            conversao = celcius * 1.8 + 32
            limpar_terminal()
            apresentação()
            print(f"Seu valor convertido Celcius {celcius}C --> Fahrenheit {conversao:.2f}")
            break
        elif escolha1 == 2: #bloco 11
            kg = float(input("Qual seu valor em Kg? "))
            conversao = kg * 1000
            limpar_terminal()
            apresentação()
            print(f"Seu valor Kg:{kg} --> Gramas:{conversao:.2f}")
            break
    
        elif escolha1 == 3: #bloco 12
            litros = float(input("escolha sua quantidade em litros: "))
            conversao = litros * 1000
            limpar_terminal()
            apresentação()
            print(f"Seu valor em litros:{litros} --> Ml{conversao:.2f}")
            break
    except ValueError: #fecha o bloco 7(try/except)
        limpar_terminal()
        apresentação()
        print("Apenas numeros, tente novamente:")

