# Microprocesadores

## Organización y Arquitectura

Cuando se describe un computador, frecuentemente se distingue entre arquitectura y organización.

* **Arquitectura**.- son los atributos de un sistema que son visibles para un programador, es decir aquellos atributos que tiene un impacto en la ejecución lógica de un programa. (conjunto de instrucciones, Nro. de bits usados para representar varios tipos de datos, mecanismos de E/S y las técnicas para direccionamiento de memoria.)
* **Organización**.- Se refiere a las unidades funcionales y sus interconexiones, que dan lugar a especificaciones arquitectónicas. (señales de control, interfaces entre el computador y los periféricos y la tecnología de memoria usada. ).

Entre los ejemplos de atributos arquitectónicos se encuentran el conjunto de instrucciones, el número de bits usados para representar tipos de datos (por ejemplo, numero, caracteres), mecanismos de E/S y tecnicas para direccionamiento de memoria.

Entre los atributos de organizaión se incluyen aquellos detalles de hardware transparentes al programador, tales como señales de control, interfaces entre el computador y los periféricos y la tecnología de memoria usada.

Para poner un ejemplo, una cuestión de diseño arquitectónico es si el computador tendrá la instrucción de multiplicar. Una cuestion de organización es si esa instrucción será implementada por una unidad especializada en multiplicar o por un mecanismo que haga un uso iterativo de la unidad de suma del sistema. La decisión de organizacion puede estar basada en la frecuencia prevista del uso de la instrucción de multiplicar la velocidad relativa de las dos aproximaciones, y el coste y el tamaño fisico de una unidad especializada en multiplicar.

> Una arquitectura puede sobrevivir muchos años, pero su organización cambia con la evolución de tecnología


## Estructura y Funcionamiento

Un computador es un sistema complejo; los computadores de hoy en día contienen millones de componentes electrónicos básicos ¿Cómo podríamos describirlos claramente? La clave esta en reconocer la naturaleza jerárquica de la maoria de los sistemas complejos. Un **Sistema jerárquico**: Conjunto de subsistemas interrelacionados cada uno de los cuales, a su vez, se organiza en una estructura jerárquica hasta que se alcanza el nivel más bajo del subsistema elemental.

* **Estructura**.- Es el modo en que los componentes están interrelacionados.
* **Funcionamiento**.- La operación de cada componente idividual como parte de la estructura

## FUNCIONAMIENTO

La figura 1.1 señala las funciones básicas que un computador puede llevar a cabo. En terminos generales hay solo cuatro:

* Procesamiento de datos
* Almacenamiento de datos
* Transferencia de datos
* Control

El computador, por supuesto, tiene que ser capaz de **procesar datos**. Los datos pueden adoptar una gran variedad de formas, y el rango de los requisitos de procesado es amplio. Sin embargo, veremos que hay solo unos pocos métodos o tipos fundamentales de procesado de datos.

![Una visión funcional de un computador](./img/funcionamiento.png)
**Figura 1.1.** Una visión funcional de un computador