# Unidad 3: Utilización del Lenguaje Python - Ejercicios de Práctica

## Módulo 4: Lenguaje Python

Esta unidad contiene ejercicios para practicar los fundamentos del lenguaje Python: identificadores, palabras reservadas, estructura de programas, declaraciones y operaciones básicas.

---

## Sección A: Identificadores y Nombres de Variables (Problemas 1-25)

### Problema 1
Indica cuáles de los siguientes son identificadores válidos en Python: `mi_variable`, `2nombres`, `_privado`, `class`, `miVariable`, `mi-variable`.

### Problema 2
Escribe un programa en Python que declare una variable para almacenar tu nombre y otra para tu edad. Imprime ambos valores.

### Problema 3
¿Por qué `for` no puede usarse como nombre de variable en Python? Menciona otras 5 palabras reservadas.

### Problema 4
Corrige los siguientes nombres de variables para que sean válidos en Python: `1er_lugar`, `mi nombre`, `return`, `precio$`, `año`.

### Problema 5
Escribe un programa que declare variables con nombres descriptivos para almacenar: el radio de un círculo, el nombre de un producto, su precio y si está disponible.

### Problema 6
¿Cuál es la diferencia entre `miVariable`, `MiVariable` y `MI_VARIABLE` en Python? ¿Cuándo usarías cada una?

### Problema 7
Escribe un programa que declare una constante para el valor de PI (3.14159) y úsala para calcular el área de un círculo.

### Problema 8
Indica si los siguientes identificadores siguen las convenciones de Python (PEP 8): `nombreCompleto`, `nombre_completo`, `NombreCompleto`, `NOMBRE_COMPLETO`.

### Problema 9
Escribe un programa que declare variables para almacenar los datos de un libro: título, autor, año de publicación, número de páginas.

### Problema 10
¿Qué sucede si intentas usar una variable antes de asignarle un valor? Escribe un programa que demuestre este error.

### Problema 11
Escribe un programa que intercambie los valores de dos variables `a` y `b` sin usar una variable temporal.

### Problema 12
Declara variables para representar una fecha: día, mes y año. Asígnales valores e imprímelos en formato DD/MM/AAAA.

### Problema 13
¿Cuál es la convención para nombrar variables que representan constantes en Python? Da 3 ejemplos.

### Problema 14
Escribe un programa que declare múltiples variables en una sola línea: `x`, `y`, `z` con valores 1, 2, 3 respectivamente.

### Problema 15
¿Por qué es importante usar nombres de variables descriptivos? Reescribe este código con mejores nombres: `a = 5`, `b = 10`, `c = a * b`.

### Problema 16
Escribe un programa que asigne el mismo valor a tres variables diferentes en una sola línea.

### Problema 17
Identifica los errores en las siguientes declaraciones: `mi variable = 10`, `123abc = "hola"`, `True = False`.

### Problema 18
Escribe un programa que declare variables para un estudiante: nombre, matrícula, calificación promedio, está inscrito.

### Problema 19
¿Qué diferencia hay entre `nombre = "Juan"` y `nombre = 'Juan'` en Python?

### Problema 20
Escribe un programa que use la función `type()` para mostrar el tipo de dato de diferentes variables.

### Problema 21
Declara una variable con un nombre que contenga guión bajo y explica cuándo es útil usar este estilo.

### Problema 22
Escribe un programa que demuestre la reasignación de variables: asigna un entero, luego una cadena, luego un flotante a la misma variable.

### Problema 23
¿Cuáles de las siguientes son palabras reservadas en Python?: `print`, `if`, `input`, `while`, `def`, `sum`.

### Problema 24
Escribe un programa que declare variables para un producto de tienda online: SKU, nombre, precio, descuento, precio_final.

### Problema 25
Investiga y lista las 35 palabras reservadas de Python. Escribe un programa que intente usar alguna como variable y observa el error.

---

## Sección B: Tipos de Datos en Python (Problemas 26-55)

### Problema 26
Escribe un programa que declare variables de tipo `int`, `float`, `str` y `bool`. Imprime cada variable junto con su tipo.

### Problema 27
¿Cuál es el resultado de `type(3.0)`? ¿Y de `type(3)`? ¿Por qué son diferentes?

### Problema 28
Escribe un programa que convierta la cadena "123" a entero y realice operaciones matemáticas con ella.

### Problema 29
¿Qué sucede si intentas sumar un entero con una cadena? Escribe un programa que demuestre el error y luego corrígelo.

### Problema 30
Escribe un programa que convierta un número flotante a entero y explica qué sucede con la parte decimal.

### Problema 31
Crea un programa que lea un número desde el teclado y determine si es entero o flotante.

### Problema 32
Escribe un programa que convierta un valor booleano a entero. ¿Cuál es el valor numérico de `True` y `False`?

### Problema 33
¿Cuál es la diferencia entre `"3.14"` y `3.14`? Escribe un programa que lo demuestre.

### Problema 34
Escribe un programa que calcule el cociente y residuo de una división usando operadores de Python.

### Problema 35
Crea un programa que determine si un número ingresado es par o impar usando el operador módulo.

### Problema 36
Escribe un programa que concatene dos cadenas y muestre el resultado. ¿Puedes "sumar" cadenas con números directamente?

### Problema 37
¿Qué tipo de dato retorna la función `input()`? Escribe un programa que lo demuestre.

### Problema 38
Escribe un programa que multiplique una cadena por un número entero. ¿Cuál es el resultado de `"Hola" * 3`?

### Problema 39
Crea un programa que convierta un entero a cadena y lo concatene con otro texto.

### Problema 40
Escribe un programa que use `int()`, `float()`, `str()` y `bool()` para convertir entre tipos de datos.

### Problema 41
¿Cuál es el resultado de `bool(0)`, `bool("")`, `bool(1)`, `bool("Hola")`? Escribe un programa que lo verifique.

### Problema 42
Escribe un programa que lea dos números del usuario y muestre su suma, resta, multiplicación y división.

### Problema 43
Crea un programa que calcule la potencia de un número usando el operador `**`.

### Problema 44
Escribe un programa que use la división entera `//` y explica la diferencia con la división normal `/`.

### Problema 45
¿Qué sucede al dividir entre cero en Python? Escribe un programa que lo demuestre.

### Problema 46
Escribe un programa que calcule el área de un triángulo usando números flotantes.

### Problema 47
Crea un programa que redondee un número flotante a 2 decimales usando la función `round()`.

### Problema 48
Escribe un programa que encuentre el valor absoluto de un número negativo.

### Problema 49
¿Cuál es el resultado de `5 / 2`, `5 // 2` y `5 % 2`? Escribe un programa que lo muestre.

### Problema 50
Escribe un programa que determine el tipo de dato de los siguientes valores: `None`, `[1, 2, 3]`, `(1, 2)`, `{"a": 1}`.

### Problema 51
Crea un programa que calcule el porcentaje de un número (ej: 15% de 200).

### Problema 52
Escribe un programa que use notación científica para representar números muy grandes o muy pequeños.

### Problema 53
¿Qué es la precisión de punto flotante? Escribe un programa que muestre el resultado de `0.1 + 0.2`.

### Problema 54
Crea un programa que convierta un número binario (como cadena) a decimal.

### Problema 55
Escribe un programa que determine el valor máximo y mínimo que puede almacenar un entero en Python.

---

## Sección C: Entrada y Salida de Datos (Problemas 56-85)

### Problema 56
Escribe un programa que solicite el nombre del usuario y lo salude: "Hola, [nombre]!".

### Problema 57
Crea un programa que lea dos números y muestre su suma con un mensaje descriptivo.

### Problema 58
Escribe un programa que solicite la edad del usuario y calcule en qué año nació.

### Problema 59
¿Cuál es la diferencia entre `print("Hola", "Mundo")` y `print("Hola" + "Mundo")`?

### Problema 60
Escribe un programa que use `print()` con el parámetro `sep` para separar valores con guiones.

### Problema 61
Crea un programa que use `print()` con el parámetro `end` para imprimir en la misma línea.

### Problema 62
Escribe un programa que solicite tres números y muestre el mayor de ellos.

### Problema 63
Crea un programa que lea el radio de un círculo e imprima su área y perímetro formateados a 2 decimales.

### Problema 64
Escribe un programa que use f-strings para formatear la salida: "El precio es $[precio]".

### Problema 65
¿Qué hace el carácter de escape `\n`? Escribe un programa que imprima texto en múltiples líneas.

### Problema 66
Crea un programa que use `\t` para crear una tabla simple de datos.

### Problema 67
Escribe un programa que solicite nombre, apellido y edad, y muestre una ficha formateada.

### Problema 68
¿Cómo imprimes una comilla dentro de una cadena? Escribe un programa que lo demuestre.

### Problema 69
Crea un programa que lea un número y muestre su cuadrado y cubo.

### Problema 70
Escribe un programa que use el método `.format()` para formatear cadenas.

### Problema 71
¿Qué diferencia hay entre `print(a, b, c)` y `print(str(a) + str(b) + str(c))`?

### Problema 72
Crea un programa que lea la base y altura de un rectángulo y muestre su área y perímetro.

### Problema 73
Escribe un programa que alinee texto a la derecha usando f-strings: `f"{variable:>10}"`.

### Problema 74
¿Cómo lees múltiples valores en una sola línea de entrada? Escribe un programa que lo haga.

### Problema 75
Crea un programa que muestre un número con formato de moneda: $1,234.56.

### Problema 76
Escribe un programa que solicite datos de un producto y muestre un recibo formateado.

### Problema 77
¿Qué hace `input("Mensaje: ")`? ¿Cuál es el propósito del parámetro?

### Problema 78
Crea un programa que lea una temperatura en Celsius y muestre su equivalente en Fahrenheit.

### Problema 79
Escribe un programa que use comillas triples para crear una cadena multilínea.

### Problema 80
¿Cómo muestras el símbolo de porcentaje en una f-string? Escribe un programa que lo haga.

### Problema 81
Crea un programa que lea el nombre y calificación de 3 estudiantes y muestre una tabla.

### Problema 82
Escribe un programa que muestre un número en formato binario, octal y hexadecimal.

### Problema 83
¿Qué sucede si el usuario ingresa texto cuando esperas un número? Escribe un programa que lo maneje.

### Problema 84
Crea un programa que simule una calculadora básica: solicita dos números y una operación.

### Problema 85
Escribe un programa que muestre una barra de progreso usando caracteres: [=====>     ] 50%.

---

## Sección D: Estructura de un Programa (Problemas 86-110)

### Problema 86
Escribe un programa bien estructurado con comentarios que calcule el promedio de 4 calificaciones.

### Problema 87
¿Cuál es la diferencia entre un comentario de una línea (`#`) y un docstring (`""" """`)?

### Problema 88
Crea un programa que incluya un encabezado con: nombre del programa, autor, fecha y descripción.

### Problema 89
Escribe un programa que tenga secciones claras: declaración de variables, entrada, proceso, salida.

### Problema 90
¿Por qué es importante la indentación en Python? Escribe un programa que cause error de indentación.

### Problema 91
Crea un programa que calcule el IMC con comentarios explicando cada paso.

### Problema 92
Escribe un programa que use constantes (variables en mayúsculas) para valores que no cambian.

### Problema 93
¿Cuántos espacios se recomiendan para la indentación en Python según PEP 8?

### Problema 94
Crea un programa que incluya validación básica de entrada usando comentarios para explicar.

### Problema 95
Escribe un programa que siga la convención de nombrado PEP 8: snake_case para variables y funciones.

### Problema 96
¿Qué es el cuerpo principal de un programa? Escribe un programa que lo identifique claramente.

### Problema 97
Crea un programa que calcule el costo de un pedido con estructura clara y comentarios.

### Problema 98
Escribe un programa que use líneas en blanco para separar secciones lógicas del código.

### Problema 99
¿Qué longitud máxima de línea recomienda PEP 8? Escribe un ejemplo de cómo dividir líneas largas.

### Problema 100
Crea un programa que incluya un bloque de código deshabilitado usando comentarios.

### Problema 101
Escribe un programa bien organizado que convierta entre diferentes unidades de medida.

### Problema 102
¿Cuál es el propósito de `if __name__ == "__main__":`? Escribe un programa que lo use.

### Problema 103
Crea un programa que tenga una sección de "configuración" al inicio con todas las constantes.

### Problema 104
Escribe un programa que calcule interés compuesto con documentación adecuada.

### Problema 105
¿Cómo organizarías un programa que realiza múltiples cálculos relacionados?

### Problema 106
Crea un programa que use nombres significativos y comentarios para ser auto-documentado.

### Problema 107
Escribe un programa que incluya ejemplos de uso en los comentarios.

### Problema 108
¿Qué información debería incluir el encabezado de un programa profesional?

### Problema 109
Crea un programa modular que podría dividirse en funciones (aunque aún no las uses).

### Problema 110
Escribe un programa que siga todas las buenas prácticas de estructura vistas en esta sección.

---

## Sección E: Operaciones y Expresiones (Problemas 111-140)

### Problema 111
Escribe un programa que evalúe la expresión: `3 + 4 * 2 - 1`. ¿Cuál es el orden de operaciones?

### Problema 112
Crea un programa que use paréntesis para cambiar el orden de evaluación de una expresión.

### Problema 113
¿Cuál es la precedencia de los operadores: `+`, `-`, `*`, `/`, `**`, `%`?

### Problema 114
Escribe un programa que calcule: ((5 + 3) * 2 - 4) / 2.

### Problema 115
Crea un programa que use operadores de comparación: `<`, `>`, `<=`, `>=`, `==`, `!=`.

### Problema 116
Escribe un programa que evalúe expresiones lógicas: `and`, `or`, `not`.

### Problema 117
¿Cuál es el resultado de `5 > 3 and 2 < 1`? Escribe un programa que lo verifique.

### Problema 118
Crea un programa que combine operadores aritméticos y de comparación.

### Problema 119
Escribe un programa que use el operador `in` para verificar si un carácter está en una cadena.

### Problema 120
¿Qué hacen los operadores `is` e `is not`? Escribe un programa que los use.

### Problema 121
Crea un programa que use asignación aumentada: `+=`, `-=`, `*=`, `/=`.

### Problema 122
Escribe un programa que calcule el valor de una expresión matemática compleja.

### Problema 123
¿Cuál es la diferencia entre `==` y `=`? Escribe un programa que lo demuestre.

### Problema 124
Crea un programa que evalúe si un número está dentro de un rango usando `and`.

### Problema 125
Escribe un programa que use el operador ternario: `valor_si_true if condicion else valor_si_false`.

### Problema 126
¿Qué retorna `10 // 3` y `10 % 3`? ¿Para qué son útiles juntos?

### Problema 127
Crea un programa que calcule si un año es bisiesto usando operadores lógicos.

### Problema 128
Escribe un programa que evalúe la expresión: `not (a > b and c < d)`.

### Problema 129
¿Cuál es el resultado de `True + True`? ¿Y de `False * 5`?

### Problema 130
Crea un programa que use la función `pow()` y compárala con el operador `**`.

### Problema 131
Escribe un programa que evalúe expresiones con paréntesis anidados.

### Problema 132
¿Qué sucede con la expresión `0 and 5/0`? ¿Por qué no hay error?

### Problema 133
Crea un programa que use `min()` y `max()` con múltiples valores.

### Problema 134
Escribe un programa que redondee números hacia arriba y hacia abajo usando `math.ceil()` y `math.floor()`.

### Problema 135
¿Cuál es el resultado de `-5 ** 2` vs `(-5) ** 2`? Explica la diferencia.

### Problema 136
Crea un programa que calcule la raíz cúbica de un número.

### Problema 137
Escribe un programa que evalúe la precedencia de `not`, `and`, `or`.

### Problema 138
¿Qué es la evaluación en cortocircuito? Escribe un programa que la demuestre.

### Problema 139
Crea un programa que use `abs()`, `round()`, `int()`, `float()` en una expresión.

### Problema 140
Escribe un programa que evalúe una fórmula de física: energía cinética, velocidad final, etc.

---

## Sección F: Problemas Integradores (Problemas 141-150)

### Problema 141
Escribe un programa completo que calcule el costo total de una compra: solicita cantidad y precio de 3 productos, calcula subtotal, IVA y total.

### Problema 142
Crea un programa que simule una calculadora de propinas: solicita el total de la cuenta y el porcentaje de propina deseado.

### Problema 143
Escribe un programa que convierta una cantidad de segundos a formato horas:minutos:segundos.

### Problema 144
Crea un programa que calcule el salario semanal: solicita horas trabajadas, tarifa por hora, y calcula con tiempo extra (después de 40 horas al 1.5x).

### Problema 145
Escribe un programa que lea los coeficientes de una ecuación cuadrática y calcule el discriminante.

### Problema 146
Crea un programa que calcule el cambio a devolver, desglosando en billetes y monedas.

### Problema 147
Escribe un programa que lea datos de un triángulo y calcule: perímetro, área (fórmula de Herón) y clasifíquelo.

### Problema 148
Crea un programa que simule el registro de un usuario: solicita nombre, email, edad y muestra un resumen formateado.

### Problema 149
Escribe un programa que calcule el costo de un viaje: distancia, rendimiento del auto, precio de gasolina, peajes.

### Problema 150
Crea un programa completo que lea datos de un empleado y calcule su nómina quincenal incluyendo deducciones.

---

## Notas para el Estudiante

- Python es un lenguaje de tipado dinámico: las variables pueden cambiar de tipo.
- Siempre convierte la entrada del usuario al tipo de dato apropiado.
- Usa nombres descriptivos para tus variables siguiendo las convenciones de Python.
- Los comentarios son importantes para documentar tu código.
- Practica escribiendo código limpio y bien estructurado desde el inicio.
