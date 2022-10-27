# Resumen de comandos de Git

* `git init` crea un nuevo repositorio
- `git status` inspecciona los contenidos de el directorio de trabajo y del **área de staging**.
* `git add` agrega cambios de archivos del directorio de trabajo al **área de staging**.
* `git diff` muestra las diferencias entre el directorio de trabajo y el **área de staging**.
* `git commit` almacena permanentemente los cambios efectuados a los archivos desde el **área de staging**.
* `git log` muestra una lista de commits previos.

# Flujo de trabajo local con git

```
git init
git add .
git commit -m "Mensaje de commit"
git add .
git commit -m "Mensaje de commit"
...
```