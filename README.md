Mexbalia

Manual: Acceso a Google Drive por medio de Javascript

1. Crear una cuenta de Google, que se usará para subir los archivos a la base de datos de HANA. 

![alt tag](https://raw.github.com/suecarmol/gDrive_P1/screencaps/ScreenCap1.png)

2. Acceder a https://www.console.developers.google.com con el usuario y contraseña de la cuenta de Google que se creó.

3. Navegar a la pestaña de APIs y activar tanto la opción de Drive API como la de SDK API, como se muestra a continuación. 

![alt tag](https://raw.github.com/suecarmol/gDrive_P1/screencaps/ScreenCap2.png)

4. Crear dos nuevos ClientIDs para aplicaciones Web, que Google usa para poder compartir información sin tener que revelar los usuarios y contraseñas de las personas. 

5. Acceder a la pestaña de Credentials y crear un nuevo ID de cliente.

6. El primer ID de cliente va a ser para localhost, para que se puedan hacer pruebas en el servidor local. 

7. El segundo ID va a ser para el servidor principal. Cabe recalcar que se debe dejar el campo de “Redirect URIs” vacío en el ID del servidor. A continuación, se presenta una imagen de la configuración de dichos IDs. 

![alt tag](https://raw.github.com/suecarmol/gDrive_P1/screencaps/ScreenCap3.png)


8. Dentro de la configuración del archivo de javascript, copiar y pegar el ClientID (del servidor o de localhost, dependiendo de en donde estés desarrollando) en una variable de configuración para que todo funcione de manera satisfactoria. 



NOTA: Recuerda que debes cambiar el ClientID si se quiere hacer la aplicación sobre otro servidor, o si se quiere pasar el contenido de localhost al servidor o viceversa. 
