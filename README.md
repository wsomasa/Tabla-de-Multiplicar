# Tabla-de-Multiplicar
Operación matemática de multipicación
mensaje_1 = "===================================="
mensaje = "Tablas de multiplicar"
mensaje_2 = "===================================="
print('\033[93m'"\n\t", mensaje_1.center(50, "="),""'\033[0m')
print('\033[93m'"\t", mensaje.center(50, "="),""'\033[0m')
print('\033[93m'"\t", mensaje_2.center(50, "="),"\n"'\033[0m')

banner = """El siguiente programa te permite multiplicar un número cualquiera,
el numero debe ser ingresado por el usuario."""

print('\033[91m',banner,'\n')

numero = int(input('\n''\033[93m'"\t""Ingrese el número que desea multiplicar: "'\033[0m'))

print('\n''\033[92m'"Quieres ver la tabla de multiplicar del número: ", numero, '\033[0m') 
for f in range (1,11):
    print('\t''\033[92m'f'{numero} x  {f} = {numero * f}''\033[0m')
