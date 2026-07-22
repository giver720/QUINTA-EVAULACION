# README - Encontrar valor máximo y mínimo en un arreglo

## Descripción
Este programa en C++ crea un arreglo de 10 números flotantes con valores predefinidos. Luego recorre todo el arreglo para identificar y mostrar el valor más grande (máximo) y el valor más pequeño (mínimo).

## Explicación paso a paso del código

1. **Inclusión de librerías**
   - Se incluye `<iostream>` para poder usar las funciones de entrada y salida (`cout` y `endl`).
   - Se usa `using namespace std;` para no tener que escribir `std::` cada vez que se utiliza algo de la librería estándar.

2. **Función principal**
   - Todo el programa se ejecuta dentro de la función `main()`.

3. **Creación del arreglo**
   - Se declara un arreglo llamado `arreglo` de tipo `float` con tamaño fijo de 10 posiciones.
   - Se le asignan estos valores predefinidos:
  
   - esto viene siendo el ejercicio 1
  


 Suma de dos matrices 3x3

## Descripción
Este programa en C++ declara dos matrices A y B de tamaño 3x3 con valores predefinidos. Luego crea una tercera matriz C y utiliza bucles anidados para sumar ambas matrices elemento por elemento. Finalmente muestra el contenido de la matriz C.

## Explicación paso a paso del código

1. **Inclusión de librerías**
   - Se incluye `<iostream>` para poder usar las funciones de entrada y salida (`cout` y `endl`).
   - Se usa `using namespace std;` para no tener que escribir `std::` cada vez que se utiliza algo de la librería estándar.

2. **Función principal**
   - Todo el programa se ejecuta dentro de la función `main()`.

3. **Declaración de la matriz A**
   - Se crea una matriz de enteros llamada `A` de tamaño 3 filas por 3 columnas.
   - Se le asignan los siguientes valores:
  


# README - Tablero de ajedrez

## Descripción
Este programa en C++ crea un tablero de ajedrez de 8x8 y coloca las piezas en su posición inicial. Utiliza letras para representar cada pieza: peones (P), torres (T), caballos (C), alfiles (A), rey (R) y reina (M). Las casillas vacías se representan con un punto (.). Al final se muestra el tablero completo en consola.

## Explicación paso a paso del código

1. **Inclusión de librerías**
   - Se incluye `<iostream>` para poder usar las funciones de entrada y salida (`cout` y `endl`).
   - Se usa `using namespace std;` para no tener que escribir `std::` cada vez que se utiliza algo de la librería estándar.

2. **Función principal**
   - Todo el programa se ejecuta dentro de la función `main()`.

3. **Creación del tablero**
   - Se declara una matriz de caracteres llamada `tablero` de tamaño 8 filas por 8 columnas.
   - Se colocan las piezas en su posición inicial de la siguiente forma:
     - Fila 0 (negras): T C A M R A C T
     - Fila 1 (peones negros): P P P P P P P P
     - Filas 2 a 5 (casillas vacías): . . . . . . . .
     - Fila 6 (peones blancos): P P P P P P P P
     - Fila 7 (blancas): T C A M R A C T

4. **Impresión del tablero**
   - Se utiliza un ciclo `for` externo que recorre las 8 filas (variable `i` de 0 a 7).
   - Dentro de él hay otro ciclo `for` que recorre las 8 columnas (variable `j` de 0 a 7).
   - En cada posición se imprime el carácter correspondiente seguido de un espacio para que se vea ordenado.
   - Al terminar cada fila se imprime un salto de línea (`endl`) para pasar a la siguiente fila.

5. **Fin del programa**
   - Se retorna `0` para indicar que el programa terminó correctamente.

## Resultado esperado
Al ejecutar el programa se mostrará el siguiente tablero:
