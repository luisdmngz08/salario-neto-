
def verificar_edad():
    print("Verificar edad para votar")

    try:
        edad = int(input("Ingresa tu edad: "))

        print("\nResultado:")

        if edad >= 18:
            print("Puedes votar.")
        else:
            print("No puedes votar.")

    except ValueError:
        print("Error: Ingresa una edad válida.")

verificar_edad()
