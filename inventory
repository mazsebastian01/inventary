nombre = input("Por favor ingrese nombre de su producto: ") #se ingresa el nombre del producto

while True: #se valida que el precio sea un float y mayor a 0
    try:
        precio = float(input("Precio: "))
        if precio < 0:
            print("El precio debe ser positivo.\n")
            continue
        break
    except ValueError:
        print("Valor incorrecto.\n")
        continue

while True: #se valida que la cantidad sea un entero y mayor a 0
    try:
        cantidad = int(input("cantidad: "))
        if cantidad < 0:
            print("El precio debe ser positivo.\n")
            continue
        break
    except ValueError:
        print("Valor incorrecto.\n")
        continue

costo_total = precio * cantidad # se realiza el calculo del costo total
print(f"Nombre del producto: {nombre}, precio del producto: {precio}, cantidad: {cantidad}, costo total: {costo_total}") # se muestra la información del producto.
