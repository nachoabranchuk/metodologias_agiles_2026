# Ejercicio Nro: 7

## Enunciado
Dar un ejemplo de cada uno de los cuellos de botellas analizados anteriormente en el paper de Brooks.

## Resolución
Complejidad: Imagina un sistema de gestión bancaria donde cada nueva funcionalidad (como un nuevo tipo de préstamo) debe interactuar con el sistema de impuestos, el historial crediticio y las notificaciones por mail. A medida que el sistema crece, el número de estados posibles aumenta exponencialmente, haciendo que sea casi imposible predecir todos los efectos laterales de un cambio.

Conformidad: Supongamos que desarrollas una aplicación de facturación en Argentina. El software debe conformarse obligatoriamente a las interfaces y regulaciones de la AFIP, que ya están establecidas y son complejas. No puedes simplificar esas reglas; el software debe adaptarse a ellas tal como son.

Cambiabilidad: Piensa en una aplicación móvil que hoy funciona perfecto, pero mañana se actualiza el sistema operativo (iOS o Android) o cambian las leyes de privacidad de datos. A diferencia de un auto que no cambia una vez fabricado, el software está bajo presión constante para modificarse solo para seguir siendo útil en un entorno que evoluciona.

Invisibilidad: Cuando intentas explicarle a un cliente la estructura de una base de datos mediante diagramas, notas que no es como un plano de una casa que se puede ver y tocar. El software está compuesto por múltiples flujos de datos y relaciones superpuestas que no tienen una representación geométrica real, lo que dificulta muchísimo que el equipo y el cliente "vean" lo mismo.
