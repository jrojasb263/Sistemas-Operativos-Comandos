# Sistemas-Operativos-Comandos

<table>
  <tr>
    <th>Comando</th>
    <th>Definicion</th>
    <th>Ejemplo</th>
  </tr>
  <tr>
    <td>ls</td>
    <td>Muestra el contenido del directorio actual.</td>
    <td>ls -l muestra el contenido en formato detallado.</td>
  </tr>
  <tr>
    <td>cd</td>
    <td>Cambia de directorio.</td>
    <td>cd /ruta/al/directorio te lleva al directorio especificado.</td>
  </tr>
 <tr>
    <td>pwd</td>
    <td>Muestra la ruta del directorio actual.</td>
    <td>pwd puede mostrar ruta como /home/ulacit</td>
  </tr>
  <tr>
<td>cat</td>
<td>Este lista, combina y escribe el contenido de los archivos en la salida estándar</td>
<td>cat archivo.txt.</td>
</tr> 
<tr>
<td>cp</td>
<td>Utiliza el comando cp para copiar archivos o directorios y su contenido</td>
<td>cp nombrearchivo.txt /inicio/nombredeusuario/Documentos</td>
</tr> 
<tr>
<td>mv</td>
<td>Mueve archivos, aunque también se puede usar para cambiar el nombre de los archivos</td>
<td>mv nombrearchivo.txt /inicio/nombredeusuario/Documentos.</td>
</tr> 
<tr>
<td>mkdir</td>
<td>Utiliza el comando mkdir para crear uno o varios directorios a la vez y establecer los permisos para cada uno de ellos</td>
<td>mkdir Musica</td>
</tr> 
<tr>
<td>rmdir</td>
<td>Para eliminar permanentemente un directorio vacío, utiliza el comando rmdir</td>
<td>rmdir -p mydir/personal1</td>
</tr> 
<tr>
<td>rm</td>
<td>El comando rm se utiliza para borrar archivos dentro de un directorio</td>
<td>rm nombredearchivo</td>
</tr> 
<tr>
<td>touch</td>
<td>El comando touch permite crear un archivo vacío o generar y modificar una marca de tiempo en la línea de comandos de Linux</td>
<td>touch /inicio/nombredeusuario/Documentos/Web.html</td>
</tr> 
<tr>
<td>grep</td>
<td>Te permite encontrar una palabra buscando entre todos los textos de un archivo específico</td>
<td>grep azul notepad.txt</td>
</tr> 
<tr>
<td>df</td>
<td>Utiliza el comando df para informar sobre el uso del espacio en disco del sistema, mostrado en porcentaje y en kilobytes (KB)</td>
<td>df -h</td>
</tr> 
<tr>
<td>chmod</td>
<td>es un comando común que modifica los permisos de lectura, escritura y ejecución de un archivo o directorio</td>
<td>chmod 777 nota.txt</td>
</tr> 
<tr>
<td>chown</td>
<td>permite cambiar la propiedad de un archivo, directorio o enlace simbólico a un nombre de usuario específico.</td>
<td>chown usuariodelinux2 nombredearchivo.txt</td>
</tr> 
<tr>
<td>wget</td>
<td>Permite descargar archivos de Internet mediante el comando wget</td>
<td>wget https://wordpress.org/latest.zip</td>
</tr> 
<tr>
<td>echo</td>
<td>Es una utilidad integrada que muestra una línea de texto o cadena utilizando la salida estándar</td>
<td>echo «Ulacit»</td>
</tr> 
<tr>
<td>useradd</td>
<td>Se utiliza para crear una nueva cuenta</td>
<td>useradd Juan</td>
</tr> 
<tr>
<td>passwd</td>
<td>Permite añadir una contraseña</td>
<td>passwd 123456789</td>
</tr> 
<tr>
<td>userdel</td>
<td>Para eliminar una cuenta de usuario</td>
<td>userdel Juan</td>
</tr> 
<tr>
<td>apt-get</td>
<td>Permite recuperar información y paquetes de fuentes autenticadas para gestionar, actualizar, eliminar e instalar software y sus dependencias</td>
<td>apt-get update</td>
</tr> 
<tr>
<td>su</td>
<td>permite ejecutar un programa como un usuario diferente</td>
<td>su [opciones] [nombredeusuario [argumento]]</td>
</tr> 
<tr>
<td>docker ps</td>
<td>Muestra los contenedores que se ejecutan en el host</td>
<td>Image ubuntu 22.04</td>
</tr> 
<tr>
<td>docker images</td>
<td>Muestra las imágenes disponibles en el host</td>
<td> Tag: <none>              image ID: 77af4d6b9913</td>
</tr> 
<tr>
<td>docker container run <image></td>
<td>Inicia un nuevo contenedor desde la imagen especificada o ejecuta un comando en un nuevo contenedor</td>
<td>docker container run ubuntu</td>
</tr> 
<tr>
<td>docker container attach <container></td>
<td>Proporciona un contenedor en ejecución con flujos locales de entrada, salida y error estándar</td>
<td>docker attach demo</td>
</tr> 
<tr>
<td>docker container update <container></td>
<td>Renueva la configuración de un contenedor</td>
<td>docker container update demo</td>
</tr> 
<tr>
<td>docker container pause <container></td>
<td>Pone en pausa los procesos que se ejecutan en un contenedor</td>
<td>docker container pause demo</td>
</tr> 
<tr>
<td>docker container stop <container></td>
<td>Detiene la ejecución de un contenedor</td>
<td>docker container stop demo</td>
</tr> 
<tr>
<td>docker container start <container></td>
<td>Reanuda la ejecución de un contenedor detenido</td>
<td>docker container start demo</td>
</tr> 
<tr>
<td>docker container rm <container></td>
<td>Elimina un contenedor del sistema</td>
<td>docker container rm demo</td>
</tr> 
<tr>
<td>nano XXXXX.sh</td>
<td>Crea un archivo de bash</td>
<td>nano script1.sh</td>
</tr> 
<tr>
<td>bash XXXXX.sh</td>
<td>Sirve para correr el archivo de bash directamente</td>
<td>bash script1.sh</td>
</tr> 

</table>
