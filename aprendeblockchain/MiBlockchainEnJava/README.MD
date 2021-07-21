Blockchain al estilo de bitcoin en Java
¿Qué necesita nuestra blockchain?
Definir la estructura de nuestras transacciones, bloques y, por supuesto, la cadena de bloques.
Nodos en nuestra red que se puedan comunicar entre si. Deben ser capaces de:
Añadir nuevos nodos a la red.
Propagar transacciones y bloques en la red.
Guardar las transacciones temporalmente en un pool de transacciones hasta que sean añadidas a un nuevo bloque.
Verificar que las transacciones y bloques recibidos son válidos de acuerdo a una serie de reglas que también definiremos.
Implementar un algoritmo de consenso, en nuestro caso Proof of Work (o Prueba de trabajo), que permita decidir que transacciones son válidas, el orden de las transacciones y, en definitiva, permitirnos enviar valor en la red evitando el doble gasto.

Podemos probar los endpoints de nuestro API REST con alguna herramienta como Postman o Insomnia