¿Qué fue lo más desafiante al trabajar con ramas y fusiones en Git?
Lo más desafiante fue entender cómo se separan y luego se combinan los cambios entre ramas, especialmente cuando varios
archivos se modifican al mismo tiempo. Al principio puede ser confuso saber en qué rama estás y cómo hacer un merge sin 
perder cambios. También, al hacer fusiones, surgieron pequeños conflictos que tuvimos que resolver manualmente.

¿Por qué es importante usar commits frecuentes con mensajes claros?
Guardar el progreso paso a paso.
Facilitar la identificación de errores si algo falla.
Permitir deshacer o regresar a un estado anterior fácilmente.
Los mensajes claros permiten a cualquier persona del equipo (incluyéndote en el futuro) entender qué se hizo y por qué, sin tener que revisar todo el código.

¿Cómo Git ayuda a evitar conflictos cuando se trabaja en equipo?

Permitir que cada miembro trabaje en su propia rama, sin afectar el trabajo de los demás.
Detectar automáticamente si hay cambios incompatibles entre ramas durante una fusión.
Ofrecer herramientas para resolver conflictos manuales, si ocurren.

Aprendimos que los conflictos no son errores, sino situaciones en las que Git no puede decidir cuál cambio mantener. Para resolverlos:
Se revisan las marcas <<<<<<<, =======, >>>>>>> en los archivos.
Se decide qué parte del código debe quedarse.
Luego se guarda, se hace git add y un nuevo commit.
Esto nos enseñó a trabajar con más atención y comunicación con el equipo para evitar editar las mismas partes del código al mismo tiempo.
