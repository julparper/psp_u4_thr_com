# Ejemplo de comunicación en monitores

La comunicación en un monitor debe hacerse dentro de los métodos synchronized.

En este escenario vamos a simular la compra de hamburguesas en el auto:

- 10 coches llegan a la hamburguesería 
- Tengo un trabajador que prepara y les da su pedido
- Cuando un trabajador ha preparado y entregado la comida al cliente, éste se va.


¿Qué ocurre si meto más trabajadores?
