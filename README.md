# Tarea-Clase-8-Husseim


## Mi Action Point
		
		Tener más horas de estudio de calidad y ser más eficiente en la busqueda de respuestas.

## Programacion imperativa vs declarativa

 1. **Imperativa:** secuencia de operaciones a realizar.
	 **Declarativa:** se especifica el resultado deseado, no cómo lograrlo.
 2. **Imperativa:** supone un mayor volumen de código ya que la secuencia de instrucciones 		    y estructuras necesarias queda expuesta en su totalidad.
	 **Declarativa:** dispone de sus procesos lógicos en capas inferiores a la que nos encontramos, resultando en códigos más livianos.
 3. **Imperativa:** de baja legibilidad, se vale de recursos básicos del lenguaje que requieren de una curva de aprendizaje para implementarlos o interpretarlos.
	 **Declarativa:** de alta carga léxica, relega en su nombre la funcionalidad que persigue. Declara intencionalidad, haciéndola altamente legible e identificable.
 4. **Imperativa:** la necesidad de replicar la secuencia de instrucciones allá donde su funcionalidad sea requerida le despoja de reusabilidad.
	 **Declarativa:** la encapsulación de procesos permite reusarlos en múltiples escenarios.
 5. **Imperativa:** se basa en el estado actual de la aplicación, mutándolo a través de instrucciones secuenciales.
	 **Declarativa:** se vale de una función pura que recibe argumentos y retorna un resultado predecible.
 6. **Imperativa:** dispone del código estrictamente necesario para atender un único escenario (lo que evita tener que implementar sistemas de seguridad adicionales) y resulta además altamente eficiente por la facilidad de estos sistemas para ser interpretado.
	 **Declarativa:** la necesidad de contemplar diferentes comportamientos de una misma función, así como evitar una reacción impredecible frente a cualquier escenario al que pueda ser expuesta.

##  Lenguajes de programacion basados en C

C es un lenguaje de programación (considerado como uno de lo más importantes en la actualidad) con el cual se desarrollan tanto aplicaciones como sistemas operativos a la vez que forma la base de otros lenguajes más actuales.

### **Características del lenguaje C**

-   Estructura de C - Lenguaje estructurado.
-   Programación de nivel medio (beneficiándose de las ventajas de la programación de alto y bajo nivel).
-   No depende del hardware, por lo que se puede migrar a otros sistemas.
-   No es un lenguaje para una tarea específica, pudiendo programar tanto un sistema operativo, una hoja de cálculo o un juego.
-   Ofrece un control absoluto de todo lo que sucede en el ordenador.
-   Organización del trabajo con total libertad.
-   Los programas son producidos de forma rápida y son bastante potentes.

### Lenguajes basados en C más utilizados

1. Python
2. Java
3. JavaScript 
4. C# (Microsoft .NET)
5. PHP
6. C/C++
7. R
8. Perl

##  Lenguajes interpretados vs. compilados

Cada programa es un conjunto de instrucciones, ya sea para sumar dos números o enviar una solicitud a través de Internet. Los compiladores e intérpretes toman código legible por humanos y lo convierten en código de máquina legible por computadora.

En un lenguaje compilado, la máquina de destino traduce directamente el programa. En un lenguaje interpretado, la máquina de destino no traduce directamente el código fuente. En cambio, un programa diferente, también conocido como intérprete, lee y ejecuta el código.

Los lenguajes compilados son convertidos directamente a código máquina que el procesador puede ejecutar. Como resultado, suelen ser más rápidos y más eficientes al ejecutarse en comparación con los lenguajes interpretados. También le dan al desarrollador más control sobre aspectos del hardware, como la gestión de memoria y el uso del CPU.

Los lenguajes compilados necesitan un paso de compilación (build), primero necesitan compilarse manualmente. Necesitas "recompilar" el programa cada vez que necesites hacer un cambio.

Algunos ejemplos de lenguajes compilados puros son C, C++, Erlang, Haskell, Rust y Go.

En cuanto a los lenguajes interpretados se puede encontrar a PHP, Ruby, Python y JavaScript.

##  Diferencias Var vs Let

1. **Let** te permite declarar variables limitando su alcance al bloque, declaración, o expresión donde se está usando.  **Var** define una variable global o local en una función sin importar el ámbito del bloque. 
2. La otra diferencia entre **var** y **let** es que este último se inicializa a un valor sólo cuando un analizador lo evalúa.
3. **Let** puede modificarse pero no volver a declararse. Cuando se utiliza **let**, no hay que preocuparse de sí se ha utilizado un nombre para una variable antes, puesto que una variable solo existe dentro de su ámbito.

##  Diferencias entre tipos de comillas

La comilla simple (') sirve para utilizar con palabras o textos, sin más.

La comilla doble (") se usa generalmente para combinar caracteres, palabras y textos que deben ser tratados como tales junto con una o varías variables, caracteres especiales... que deben ser sustituídos por su correspondiente valor, todo ello en una misma instrucción.

Las comillas invertidas (backticks) (`) tienen una gran utilidad en el script. Son muy utilizadas ya que convierten en variable el resultado de una instrucción o comando. Las comillas invertidas permiten la interpolación de variables y expresiones dentro del string, mientras que las comillas simples y dobles no lo permiten.
