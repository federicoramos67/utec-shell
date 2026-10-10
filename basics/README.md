# Shell, introduccion

Scripts de Bash para practicar navegacion, listados, manipulacion de archivos y enlaces simbolicos.

Cada script contiene dos lineas y es ejecutable. Los scripts que cambian de directorio se cargan con `source` para modificar la shell actual.

| Archivo | Descripcion |
|---|---|
| 0-current_working_directory | Imprime la ruta absoluta del directorio actual. |
| 1-listit | Lista el contenido del directorio actual. |
| 2-bring_me_home | Cambia al directorio personal al cargarlo con source. |
| 3-listfiles | Lista el contenido en formato largo. |
| 4-listmorefiles | Lista en formato largo e incluye archivos ocultos. |
| 5-listfilesdigitonly | Lista archivos ocultos con IDs numericos de usuario y grupo. |
| 6-firstdirectory | Crea /tmp/my_first_directory. |
| 7-movethatfile | Mueve betty al primer directorio. |
| 8-firstdelete | Elimina betty del primer directorio. |
| 9-firstdirdeletion | Elimina el primer directorio vacio. |
| 10-back | Vuelve al directorio anterior al cargarlo con source. |
| 11-lists | Lista el directorio actual, su padre y /boot en formato largo con ocultos. |
| 12-file_type | Muestra el tipo de /tmp/iamafile. |
| 13-symbolic_link | Crea el enlace simbolico __ls__ a /bin/ls. |
| 14-copy_html | Copia archivos HTML nuevos o mas recientes al directorio padre. |
| 15-lets_move | Mueve los archivos que empiezan con mayuscula a /tmp/u. |
| 16-clean_emacs | Elimina los archivos de respaldo que terminan en ~. |
| 17-tree | Crea la estructura welcome/to/school. |
