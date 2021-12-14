# Test project
Este proyecto está hecho para que sirva de caja de arena para el que quiera probar

Por ejemplo:
* crear una rama
* hacer push a cualquier rama
* hacer pull desde la misma rama
* hacer pull desde otra rama
* hacer un merge request
* crear issues, asociarlos a milestones, ponerle etiquetas, cerrarlos, comentar etc.
* crear milestones
* poner comentarios
* consultar el historial de commits
* comparar ramas
* generar conflictos:
  * alguien hace push a una rama
  * no haces pull
  * haces cambios y comiteas
  * pusheas
    * si es el cambio es en archivos distintos no debe pasar nada
    * si el cambio es en el mismo archivo puede que haya conflicto
    * si el cambio afecta a mismas líneas va a haber conflictos
* solucionar conflictos

Voy a proteger la rama main para que no podáis hacer push a ella.
 * comprobar que no podéis hacer push
 * solicitar un merge request de alguna rama a main
