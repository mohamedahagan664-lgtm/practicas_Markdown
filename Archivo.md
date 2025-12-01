# Comandos Básicos en linux para empezar
## Comandos que hay que conocer

| Comando | Descripción |
|---------|-------------|
| man     | Muestra el manual de usuarios de un comando específico. Si lo escribes primero y luego escribes otro comando, verás para qué sirve ese otro comando. |
| clear   | Este comando limpia el terminal y deja la ventana en blanco eliminando todo lo que se había hecho y escrito antes. |
| sudo    | Es la abreviatura de "superuser do" y es un comando que fuerza una acción como si fueras un superusuario. Esto quiere decir que harás acciones como administrador, con careas que solo pueden realizarse si tienes credenciales de superusuario, como instalar aplicaciones, modificar archivos o configuraciones. Va antes del resto de comandos de la acción .|
| history | Este comando muestra una lista con el historial de comandos que has utilizado en el terminal durante la última sesión. |

## Comandos básicos de directorios
| Comando | Descripción |
|---------|-------------|
| pwd     | Te muestra el directorio en el que estás ahora mismo, y así poder saber la estructura de directorios del sistema en el que estás |
| cd      | El nombre significa Change Directory, y sirve para cambiar de directorio. Esto quiere decir que sirve para cambiar de carpeta. Si escribes CD a solas, irás a tu Home, tu carpeta personal. |
| cd dirección/dierctorio | Te permite ir a un directorio concreto |
| cd ..   | Vas al documento padre. Esto quiere decir que si estás en una subcarpeta, pasarás a la carpeta anterior del que estabas. |
| cd -    | Vas al directorio anterior en el que estabas. Por ejemplo, si estás haciendo algo en uno y luego saltas a otro totalmente diferente para hacer una tarea concreta, con este vuelves al que estabas antes. |
| ls      | Te muestra una lista con los archivos y directorios que hay dentro del directorio actual en el que estás |
| mkdir   | Crea un nuevo directorio en el sitio donde estás del sistema de archivos. |
| rmdir   | Borra y elimina un directorio vacío del sistema. |

## Comandos básicos para archivos
| Comando | Descripción |
|---------|-------------|
| find    | Sirve para buscar archivos y directorios en el sistema. |
| cp      | Sirve para copiar archivos y directorios de un lugar a otro, tendrás que usarlo escribiendo lo que quieres copiar y a dónde. Por ejemplo, usando el formato cp archivo_a_copiar.txt nuevo_archivo.txt |
| mv      | Sirve para mover archivos y directorios de un lugar a otro, tendrás que usarlo escribiendo lo que quieres mover y a dónde, de forma que desaparezca de donde estaba antes. Puedes usar mv archivo_origen carpeta_destino/ |
| rm      | Elimina archivos y directorios. |
| wget    | Sirve para descargar y recuperar contenidos de Internet, escribiendo el comando seguido de la dirección del programa que quieras. |
| head    | Busca las primeras líneas de código de un archivo, para poder identificarlo bien. |
| tail    | Te muestra también el contenido de un archivo, mostrando solo las 10 últimas líneas de código de este. |
| grep    | busca patrones dentro de un archivo |
| cat     | Sirve para visualizar, unir y crear archivos. Por ejemplo, si lo escribes antes del nombre de un archivo, verás el contenido de este archivo. |
| wc      | Te hace un recuento de las palabras que tiene un archivo de texto. |
| less    | Reduce la cantidad de contenido de un archivo que se ve, para verlo una página a la vez y que sea más fácil de leer. |
| touch   | Te permite actualizar los tiempos de acceso y modificación de unos archivos, como por ejemplo la última vez que editaste un archivo. Sin embargo, también sirve para crear un nuevo archivo en blanco. |
| chmod   | Te permite cambiar el modo de un archivo, pudiendo añadir o quitar el modo r (leer), w (escribir) o x (ejecutar). Por ejemplo, con chmod +x script |
| unzip   | Te permite descomprimir un archivo comprimido en formato zip. Después del comando tendrás que escribir el nombre del archivo. |
| ./      | Si escribes este comando seguido de un nombre de archivo, ejecutarás ese archivo con el programa compatible que tengas instalado. |
| kill    | Si hay algún programa que no te responde, con el comando kill seguido del nombre del programa puedes forzar su cierre. |
| shred   | Este comando seguido del nombre de un archivo borrará el contenido de este archivo de forma repetida para que sea casi imposible de recuperarlo. No solo lo borras, también lo destrozas para que no se recupere. |









