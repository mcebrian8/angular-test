# Angular Test

Proyecto base de ejemplo de aplicación angular.

```
export const HEROES: Hero[] = [
  { id: 11, name: 'Dr Nice' },
  { id: 12, name: 'Narco' },
  { id: 13, name: 'Bombasto' },
  { id: 14, name: 'Celeritas' },
  { id: 15, name: 'Magneta' },
  { id: 16, name: 'RubberMan' },
  { id: 17, name: 'Dynama' },
  { id: 18, name: 'Dr IQ' },
  { id: 19, name: 'Magma' },
  { id: 20, name: 'Tornado' }
];
```

## Ejercicios

Como se puede ver ahora mismo se están mostrando como Top Heroes a: Narco, Bombasto, Celeritas y Magneta.
Todos los ejercicios salvo el último, se pueden resolver con una linea de código.

1. Dashboard: La lista de Top Heroes en la pantalla de dashboard deberia mostrar **solo los 3 primeros elementos de la lista**.
   *(Resultado esperado => Dr Nice, Narco y Bombasto)*

2. Dashboard: Las lista de Top Heroes deberá aparecer con el nombre del heroe seguido de su **ID entre parentesis**.
   *(Resultado esperado => De Nice (11), Narco (12), Bombasto (13))*

3. Heroes: Implementar una validación en el alta de nuevos heroes donde **no permita** dar de alta Heroes que comiencen por **"A"**.
   *(Resultado esperado => Añadir "Aquaman" no será posible, pero sí "Goku")*

4. Dashboard: La lista de top heroes en la pantalla de dashboard solo deberian aparecer aquellos cuya **longitud de su nombre sea igual o mayor a 5 letras**.
   *(Resultado esperado => Dr Nice (11), Bombasto (12) y Celeritas (14))*

5. Heroes: Añadir debajo de la lista de heroes el texto **"Member count: XX"**, donde XX sea el número de heroes incluidos en la lista.

6. Añadir una **nueva opción** en el Tour of Heroes tras Dashboard y Heroes que se llame **Help**. En esta vista simplemente se mostrará el texto **"Gracias"**.
