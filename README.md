# jsFramework Instalador

<h2>Requisitos para instalar el Framework</h2>

<p>Este Instalador solo funciona para sistemas linux debian, debe tener instaladas las siguientes aplicaciones:</p>
<br>
<ul>
  <li>Git</li>
  <li>Apache2</li>
  <li>Mysql o MariaDB</li>
  <li>PHP 5*</li>  
</ul>
<br>
<h2>Ejecución</h2>
<br>
<p>Este archivo se puede ejecutar por consola ejecutando:</p>
<br>
./jsFrameworkInstall.sh
<br>

<h2>Pasos de Instalación</h2>
<br>
<p>Lo primero que hace la instalación es verificar que git y la ruta de apache por defecto existan, si esto es satisfactorio el instalador pide el nombre de la aplicación a crear, si no hay ningún proyecto creado con ese nombre en la raiz de esa carpeta lo crea y procede a descargar los archivos de git. Seguido de esto pide el usuario y contraseña de mysql para instalar la BD y crear el archivo de conexion de la aplicacion que se llama datos.php</p>
<br>
<p>Hecho esto ya es posible entrar al localhost y entrar al directorio con el nombre que se le dio al inicio de la instalación.</p>




