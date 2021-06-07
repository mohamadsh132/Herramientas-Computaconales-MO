# Herramientas-Computaconales-MO
Proyecto Herramientas Computacionales 

_ Marckdown_

**Explicacion del problema**

1. Elaborar un algoritmo para calcular el área de un triángulo cuya altura es de 30 cm y la base de 50 cm. Realizar una versión genérica de este algoritmo para calcular el área de un triángulo dada una altura y una base cualquiera,¿Qué cambio se debe hacer? 

altura= 50           **Variable de altura**

base= 30             **Variable de base**

area= (base*altura)/2           **Ecuacion de la area para poder calcular**

print("la area del triangulo es: ", area)

**# Lo que se va imprimir mas el resultad el cual es la area**

2. Elaborar un algoritmo para calcular la nota final de un curso con la siguiente distribución de
evaluaciones: 2 parciales (25% cada uno), taller (20%) y proyecto (30%)


print("calcular la nota final del curso")

parcialuno= float(input("ingrese valor del parcial uno : "))

parcialdos= float(input("ingrese valor del parcial dos : " ))

taller= float(input("ingrese valor del taller : "))

proyecto= float(input("ingrese valor del proyecto : " ))

notaFinal = (parcialuno*0.25 + parcialdos*0.25 + taller*0.20 + proyecto*0.30)

if parcialuno <= 5 and parcialdos <= 5 and taller <=5 and proyecto <= 5:

    print( "la nota final es: " , notaFinal)
    
else:

    print(" No es correcto ")
    
3. Elaborar un algoritmo que realice la transformación de grados Celsius a Fahrenheit

TemperaturaCelsius=float(input("ingrese la temperatura en Celcius : "))

valor1=(TemperaturaCelsius * 9) / 5

valor2= (valor1 + 32)

print("La temperatura en Fahrenheit es: ", valor2)


5. Elaborar un algoritmo casa de cambio, que reciba una cantidad de dinero en pesos colombianos y realice su equivalente en dólares, yenes y euros, tenga en cuenta que el cambio deberá realizarse a la tasa representativa de cada moneda (actual) y que la casa de cambio, incluye un 2% de ganancia a ese valor. 

def dolares(pesos):

    dolares= float(pesos / 3517)//1
    
    ganancia=float(pesos*0.2)//1
    
    Gcasa= dolares-ganancia
    
    print(dolares)
    
    return(Gcasa)

def yenes(pesos):

    yenes= float(pesos/34.52)//1
    
    ganancia=float(pesos*0.2)//1
    
    Gcasa= yenes-ganancia
    
    print(yenes)
    
    return(Gcasa)

def euros(pesos):

    euros= float(pesos/ 4.313)//1
    
    ganancia=float(pesos*0.2)//1
    
    Gcasa= euros-ganancia
    
    print(euros)
    
    return(Gcasa)

dolares(8000)

yenes(8000)

euros(8000)
