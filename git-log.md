# git log
Muestra todo el historial de commits del proyecto

`
git log --pretty=format:"%h - %an, %ar : %s"
`
Muestra el historial con el formato que indicamos.

## Limitar la salida del historial

`git log -n`: Cambiamos la n por cualquier número entero, por ejemplo:
`git log -2` nos mostrará los 2 commits más recientes.

`git log --after="2017-01-26 00:00:00"`: Muestra los commits realizados antes de la fecha especificada.

Las banderas del comando `git log` se pueden usar juntas según nos convenga, por ejemplo:
`git log --after="2017-01-25 12:00:00" --before="2017-01-26 12:30:00"`
`git log --graph ` muestra un pequeño grafico

`git log --oneline`
Este comando nos muestra el historial en una sola linea por commit
