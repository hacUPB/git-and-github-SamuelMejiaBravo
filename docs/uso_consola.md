# Descripción de uso de consola

1. Conceptos básios de navegación:
<cd> se utiliza para cambiar de directorio, para volver se añade un "..".
<ls> imprime los archivos y carpetas, si se le añade un -al muestra los ocultos también.
<pwd> indica la ubicación en la que se encuentra actualmente.
2. Crear directorios y archivos:
<mkdir> crea carpetas.
<touch> crea archivos.
<mv> mueve o cambia el nombre de un archivo.
<rm> elimina un archivo/carpeta.
3. Guardar archivos:
<git init> inicializa un repositorio.
<branch> cambia el branch en el que se guarda.
<vim> abre el editor de git.
<git add "nombre"> añade archivos al guardado, con "." en el nombre añade TODO.
<git commit -m "mensaje"> hace un guardado local del archivo. Hay que presionar "i" para iniciar la edición y luego esc y escribir ":x" para salir nuevamente a la consola.
<git remote add "nombre" "url"> establece conexión remota para cargar los archivos a GitHub.
<git remote -v> visualiza la conexión.
<git push -u "conexión" "branch"> envía los datos a la conexión remota.
