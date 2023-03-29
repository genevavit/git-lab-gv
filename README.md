Comandos
# Comandos 
- git init: Inicializar un repositorio y habilitar la configuración del directorio actual para poder realizars control de versiones.
- git add: Agregar archivos nuevos para que estén configurados para control de versiones, etapa anterior al commit.
- git commit: Etapa anterior al push para realizar actualizaciones sobre archivos pero solo dentro del repositorio local.

# Al realizar ediciones tanto la primera vez como veces posteriores al archivo README.md, debemos siempre colocar el comando
# git add README.md
# Podemos revisar el estatus de los archivos del repo local con
# git status
#y así ver s estos archivos estánconfigurads dentro del control de versiones

# Luego de esto, se realiza el commit con 
# git commit -m "mensaje"

# Debajo se sigue documentando nuestro README.md 
- git diff <archivo>: Mostrar las diferencias entre el archivo siendo modificado y al último que se le hizo commit en esa rama.
- git diff <hash> <archivo>: Mostrar las diferencias entre el archivo siendo modificado y cualquier archivo con versión anterior que deseamos.
- git branch <nombre de la rama>: Permite crear una rama principal y ramas a partir de esa rama principal.
- git checkout: Permite viajar entre 2 ramas distintas y devolverse cuando desea.
- git merge: Permite unir 2 ramas en una sola, en esta se resuelven conflictos.
- git revert <ID>: Permite volver a una línea de tiempo anterior sin perder las líneas de tiempo futuras a ella y también sin perder los commits.
- git reset: Elimina líneas de tiempo

