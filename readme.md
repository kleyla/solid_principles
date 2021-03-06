# SOLID PRINCIPLES

Los principios SOLID tienen mucho que ver con POO.

- Single Responsability
- Open close
- Liskov sustitution
- Interface segregation
- Dependency Inversion

1. Single Responsibility

Responsabilidad unica: Una clase una y solo una razon para cambiar.

2. Open close

Abierto cerrado: Las entidades deben estar abiertas a extension, pero cerradas a modificacion.

Ej. Una mano, con una mano se puede realizar muchas acciones, pero no te la quitas y la abres por cada cosa nueva que vayas a hacer con ella.

Separa el comportamiento extensible detras de una interfaz y voltea las dependencias.

3. Liskov sustitution

Sustitucion de Liskov: Si S es un subtipo de T, entonces los objetos de tipo T pueden ser sustituidos por objetos del tipo S.

4. Interface segregation

Segregacion de interfaces: Ningun cliente debe ser forzado a depender de metodos que no usa. Segregar = apartar, dividir al usar interfaces. Favorecemos al desacoplamiento mas que acoplamiento.

5. Dependency Inversion:

Los modulos de alto nivel no deben depender de los modulos de bajo nivel. Ambos deben depender de abstracciones. Las abstracciones no deben depender de los detalles, los detalles deben depender de las abstracciones.

Abstraccion: Def. Separar por medio de una operacion intelecctual un rasgo o una cualidad de algo para analizarlos aisladamente. En programacion logramos la abstraccion usando interfaces o clases abstractas.
