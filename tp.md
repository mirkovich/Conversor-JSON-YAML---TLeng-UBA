# Conversor  de JSON a YAML


## Lenguaje de entrada: JSON

Json es un formato de intercambio de datos. Define dos tipos de escructuras. 

* Objeto: es un conjunto no ordenado de pares clave/valor. Osea un diccionario: {clave:valor, ... , clave:valor}.

**si bien JSON no exige que las claves de un objeto sean únicas, se deberá verificar que lo sean dado que es un requisito de YAML**

* Arreglo: una secuencia ordenada de valores. [valor,valor, ..... , valor ].

**VALOR:** es un objeto, arreglo, o valor individual(números, valores de verdad, null).

toda tabulación que no se encuentre dentro de una cadena son ignorados.

## Lenguaje de salida: YAML

Lenguaje de serielización, tiene las mismas estructuras que JSON (se llaman mapeos y secuencias, y los valores individuales son llamados escalares), pero hay mas y es mas extendible.

Los mapeos y secuencias se pueden notar como se hacen en JSON. Se llama estilo ** flow**.
También se puede representar con una linea por elemento, sin marcadores de comienzo ni fin, estos son marcados por el **nivel de identación** se conoce como estilo **block**.

**la identación debe realizarse exclusivamente con espacios, sin tabulaciones**