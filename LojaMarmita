print("------ Bem-vindo à Loja de Marmitas do Jason Santos ------")
print("-----------------------------------------------------------")
print("                        Cardápio                           ")
print("-----------------------------------------------------------")
print("| Tamanho | Bife Acebolado(BA) | Filé de Frango(FF)        |")
print("|---------|--------------------|---------------------------|")
print("|   P     |     R$ 16.00       |     R$ 15.00              |")
print("|   M     |     R$ 18.00       |     R$ 17.00              |")
print("|   G     |     R$ 22.00       |     R$ 21.00              |")
print("-----------------------------------------------------------")

total = 0

while True:
    # Entrada e validação do sabor
    sabor = input("\nEntre com o sabor desejado (BA/FF): ").upper()
    if sabor not in ['BA', 'FF']:
        print("Sabor inválido. Tente novamente")
        continue

    tamanho = input("Entre com o tamanho desejado (P/M/G): ").upper()
    if tamanho not in ['P', 'M', 'G']:
        print("Tamanho inválido. Tente novamente")
        continue

    if sabor == 'BA':
        if tamanho == 'P':
            valor = 16
        elif tamanho == 'M':
            valor = 18
        else:
            valor = 22
        print(f"Você pediu um Bife Acebolado do tamanho {tamanho}: R$ {valor:.2f}")

    elif sabor == 'FF':
        if tamanho == 'P':
            valor = 15
        elif tamanho == 'M':
            valor = 17
        else:
            valor = 21
        print(f"Você pediu um Filé de Frango no tamanho {tamanho}: R$ {valor:.2f}")

    total += valor

    mais = input("\nDeseja mais alguma coisa? (S/N): ").upper()
    if mais != 'S':
        break

print(f"\nO valor total a ser pago: R$ {total:.2f}")
