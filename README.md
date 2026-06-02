# Bitácora de Bandit

Documentación de mi aprendizaje en seguridad.



bandit0@bandit:\~$ ls

readme

bandit0@bandit:\~$ cat readme

Congratulations on your first steps into the bandit game!!

Please make sure you have read the rules at https://overthewire.org/rules/

If you are following a course, workshop, walkthrough or other educational activity,

please inform the instructor about the rules as well and encourage them to

contribute to the OverTheWire community so we can keep these games free!



The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If



\## Nivel 0 -> 1

\- \*\*Objetivo\*\*: Obtener la contraseña del nivel 0.

\- \*\*Comando utilizado\*\*: `ls` (para listar) y `cat` (para leer el archivo).

\- \*\*Resultado\*\*: Contraseña extraída con éxito del archivo `readme`.


bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
bandit1@bandit:~$

## Nivel 1 -> 2
- **Objetivo**: Leer un archivo cuyo nombre es `-`.
- **Comando clave**: `cat ./-`
- **Lección aprendida**: En Linux, el símbolo `-` al inicio de un nombre de archivo suele interpretarse como un parámetro (opción). Al usar `./`, forzamos al sistema a tratarlo como un archivo local dentro del directorio actual, evitando errores de sintaxis.

