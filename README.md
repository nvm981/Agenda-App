	Descripción del proyecto
Este proyecto consiste en desarrollar una aplicación móvil para Android enfocada en la administración de información personal mediante una agenda digital. La aplicación permite a los usuarios registrarse e iniciar sesión para acceder a un entorno donde pueden gestionar sus contactos y notas personales de manera organizada y sencilla.
El objetivo principal es ofrecer una herramienta intuitiva que facilite el almacenamiento y administración de información importante desde un dispositivo móvil. La aplicación ha sido desarrollada utilizando Kotlin y Jetpack Compose, aplicando una arquitectura organizada que favorece el mantenimiento del código y una experiencia de usuario moderna.
La aplicación integra diferentes módulos que trabajan de forma conjunta para brindar una solución completa, incluyendo autenticación de usuarios, administración de contactos, gestión de notas y navegación entre las distintas pantallas. Su desarrollo permitió aplicar los conocimientos adquiridos durante el curso de Desarrollo de Aplicaciones Android, implementando buenas prácticas de programación y diseño de interfaces.

	Exposición del problema
Actualmente muchas personas utilizan aplicaciones diferentes para administrar sus contactos, registrar notas personales o almacenar información importante, lo que puede provocar desorganización y dificultar el acceso rápido a sus datos. Además, algunas aplicaciones incluyen funciones innecesarias o presentan interfaces complejas que afectan la experiencia del usuario.
Como resultado, surge la necesidad de contar con una aplicación sencilla, organizada y fácil de utilizar que permita centralizar la información personal en un solo lugar. AgendaApp Kotlin JC busca solucionar esta situación ofreciendo una interfaz moderna que facilite la administración de contactos y notas, permitiendo al usuario acceder a su información de forma rápida y eficiente.

	Plataforma
La aplicación fue desarrollada para dispositivos móviles con sistema operativo 	Android utilizando Android Studio como entorno de desarrollo.
		
	Tecnologías utilizadas

•	Kotlin
•	Android Studio
•	Jetpack Compose
•	Material Design 3
•	Navigation Compose
•	ViewModel
•	Gradle
•	Git y GitHub

	Interfaz de usuario
		La aplicación ofrece una interfaz limpia, organizada y fácil de utilizar, 	compuesta por las siguientes pantallas principales:

•	Inicio de sesión.
•	Registro de usuarios.
•	Pantalla principal.
•	Gestión de contactos.
•	Lista de contactos.
•	Agregar contactos.
•	Editar contactos.
•	Gestión de notas.
•	Lista de notas.
•	Crear notas.
•	Editar notas.

	Interfaz de administración
		Implementa una estructura interna basada en ViewModels para 	administrar 	el estado de cada módulo y organizar la lógica de negocio, permite:
•	Gestionar la autenticación de usuarios.
•	Administrar la información de contactos.
•	Controlar la creación y edición de notas.
•	Mantener la navegación entre pantallas.
•	Facilitar el mantenimiento y escalabilidad del proyecto.

	Funcionalidad
o	La aplicación incluye las siguientes funciones principales:
o	Registro de nuevos usuarios.
o	Inicio de sesión mediante autenticación.
o	Navegación entre las diferentes pantallas de la aplicación.
o	Creación de nuevos contactos.
o	Visualización de la lista de contactos.
o	Edición de contactos existentes.
o	Creación de notas personales.
o	Visualización de la lista de notas.
o	Edición de notas existentes.
o	Administración del estado de la aplicación mediante ViewModels.
o	Interfaz desarrollada completamente con Jetpack Compose.
o	Organización del proyecto siguiendo una estructura modular que facilita futuras mejoras y el mantenimiento del código.

Flujo de uso de la aplicación
1.	Registro de usuario.
Al iniciar la aplicación por primera vez, el usuario debe crear una cuenta para poder acceder a las funcionalidades disponibles. Para ello, completa el formulario de registro ingresando la información solicitada, como nombre de usuario y contraseña. Una vez registrados los datos correctamente, la cuenta queda almacenada en la base de datos y el usuario podrá iniciar sesión cuando lo desee. 
 
2.	Inicio de sesión.
Después de registrarse, el usuario accede a la aplicación mediante la pantalla de inicio de sesión, donde introduce su nombre de usuario y contraseña. El sistema valida las credenciales ingresadas y, si son correctas, permite el acceso al menú principal. En caso de que los datos sean incorrectos, se muestra un mensaje de error para que el usuario pueda volver a intentarlo.
 

3.	Acceso al menú principal.
Una vez autenticado, el usuario ingresa al menú principal de la aplicación, desde donde puede acceder a todas las funcionalidades disponibles. En esta pantalla se presentan las opciones para crear nuevas notas, visualizar las notas existentes, administrar los contactos registrados y utilizar la función de búsqueda para localizar información de forma rápida.
 

4.	Creación de notas.
Al seleccionar la opción para crear una nueva nota, se muestra un formulario compuesto por un campo para el título o encabezado de la nota y un área de texto destinada a la descripción o contenido. Después de completar la información, el usuario presiona el botón Guardar, momento en el cual la nota se almacena en la base de datos y queda disponible para futuras consultas.
 
5.	Visualización y edición de notas.
Las notas guardadas se presentan en una lista organizada para facilitar su consulta. Cada registro cuenta con un icono de edición representado por un lápiz, el cual permite modificar el título o el contenido de la nota cuando sea necesario. Una vez realizados los cambios, el usuario puede guardar nuevamente la información para actualizar los datos almacenados.
    	
6.	Administración de contactos.
La aplicación permite registrar contactos personales mediante un formulario donde se ingresan datos como el nombre, número telefónico y demás información requerida. Al guardar el registro, el contacto pasa a formar parte de la agenda y puede ser consultado en cualquier momento.
 

7.	Consulta de la lista de contactos.
Todos los contactos registrados se muestran en una lista que facilita su localización y administración. Desde esta vista, el usuario puede revisar la información almacenada y seleccionar el contacto con el que desea interactuar.
 

8.	Gestión de contactos.
Cada contacto dispone de diferentes opciones de administración. El usuario puede editar la información para mantenerla actualizada, eliminar el registro cuando ya no sea necesario, realizar una llamada telefónica directamente desde la aplicación o enviar un mensaje SMS utilizando el número almacenado.
   

9.	Cierre de sesión.
Cuando el usuario finaliza el uso de la aplicación, puede cerrar su sesión mediante el icono correspondiente ubicado en el menú principal. Esta acción finaliza el acceso a la cuenta de forma segura y redirige nuevamente a la pantalla de inicio de sesión, evitando que otras personas puedan acceder a la información personal del usuario.
 
 


