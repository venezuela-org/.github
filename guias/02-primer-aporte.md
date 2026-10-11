# Guía 02 · Tu primer aporte

Un cambio pequeño, de principio a fin, para ver cómo funciona todo. No hace falta instalar nada.

## Opción A: una tarea real del tablero

1. Abre el tablero de la organización y filtra por la etiqueta `primera-tarea`.
2. Comenta en el issue "la tomo". Queda asignado a ti.
3. Abre el archivo que el issue indica, pulsa el lápiz (Edit), haz el cambio y elige "Create a new branch for this commit and start a pull request".
4. En el pull request, escribe qué cambiaste y por qué, y pega el número del issue (por ejemplo "Cierra #12").
5. Otra persona lo revisa. Con una aprobación se integra y el issue se cierra solo.

## Opción B: el ejercicio de los tres cambios

La organización mantiene una copia del ejercicio docente "de 25 a 26" en el repositorio `primer-aporte` (plantilla; la atribución del material original está en su archivo LICENSE).

1. Entra al repositorio y pulsa "Use this template", "Create a new repository". Ya tienes tu copia.
2. Abre `datos/mediciones.csv` y cambia el primer 24 por 30. Guarda el commit.
3. Ve a Actions, "01 - Analizar datos", y abre la ejecución que acaba de empezar. El resumen muestra promedio 26, mínimo 23, máximo 30. Nada que descargar.
4. El mismo commit produce un gráfico (02) y, si editas `ejemplos/informe.md`, un PDF (03).

Eso es todo el ciclo: cambias un archivo, una automatización hace el trabajo, el resultado queda ligado a tu commit. Lo mismo vale para una tesis, una clase o una línea de Conexión RedJIV.

## Después

Si tu aporte es sustancial, añade tu nombre o seudónimo y tu ORCID a `CITATION.cff` del repositorio, con tu rol (ver Guía 03).
