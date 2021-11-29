# app-tareas-demo
Servicio Web Spring Boot<br/>

El servicio web fue creado con Spring Boot 2.5.6 y Sql Server 2019.<br/>

Para ejecutar el servicio primero descargue el zip compilado (demo-tareas.zip), ademas el script de la base de dato (script.db.txt)<br/>

# Script Base de Datos "PRUEBAS"<br/>
Copiar el contenido de "script.db.txt"<br/>
Abrir Sql Server 2012 o superior<br/>
Iniciar su instancia<br/>
Abrir pestaña "New Query"<br/>
Copiar el contenido previo<br/>
Ejecutar (F5)<br/>

# Servicio Web
Para ejecutar el servicio web, ejecute Spring Tool Suite 4<br/>
Diríjase a File -> Import...<br/>
Expandir General -> Seleccionar "Existing Projects into Workspace"<br/>
Seleccionar "Select archive file:" y buscar el zip descargado "demo-tareas.zip"<br/>
Luego click en Finish<br/>
Expandir src/main/resource
Abrir "application.properties"
Modificar Servidor, Usuario y Password de la conexión Sql Server
Ejecutar el servicio.<br/>
