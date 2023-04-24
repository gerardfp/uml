# Diagramas de clases

En ingeniería de software, un diagrama de clases en el lenguaje de modelado unificado (UML) es un tipo de diagrama de estructura estática que describe la estructura de un sistema al mostrar las clases del sistema, sus atributos, operaciones (o métodos) y las relaciones entre objetos.

En un diagrama de clases podemos encontrar los siguientes elementos:
- Clases: son abstracciones del dominio del sistema que representan elementos del mismo mediante un estado (campos) y un comportamiento (métodos). Los campos y métodos tienen una visibilidad que determina quién puede acceder a ellos.
- Relaciones: en el diagrama representan relaciones reales entre los elementos del sistema a los que hacen referencia las clases. Pueden ser de herencia, composición y agragación (entre otras).
- Notas: Se representan como un cuadro donde podemos escribir comentarios que nos ayuden a entender algún concepto que queramos representar.
- Elementos de agrupación: Se utilizan cuando hay que modelar un sistema grande, entonces las clases y sus relaciones se agrupan en paquetes, que a su vez se relacionan entre sí.

## Clases
La representación de una clase en UML consiste en una caja con tres compartimentos: nombre, campos y métodos.
- Nombre de la clase
- Campos
- Métodos

Se especifica la visibilidad de los miembros de la clase con los símbolos `+

```mermaid
classDiagram
  class Nombre {
    +tipo campo
    +metodo()
  }
 ```
