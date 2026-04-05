Esta aplicación esta desarrollada para capturar eventos del sistema. 
El objetivo es implementar un Broadcast Receiver que escuche el momento en que el usuario desbloquea la pantalla del dispositivo.
Cuando el sistema detecta el desbloqueo (Intent.ACTION_USER_PRESENT), la aplicación realiza lo siguiente:
Muestra un mensaje Toast en la pantalla con el texto: "Pantalla desbloqueada detectada".
Registra un mensaje en el Logcat para indicar que el evento se produjo correctamente.
Utiliza un Intent implícito para abrir la aplicación de llamadas del celular con un número dado.

Para este trabajo implementamos:
Broadcast Receiver: Se creó una clase interna para recibir la señal del sistema.
Intents: Se usó un Intent para la navegación entre nuestra aplicación y la aplicación de llamadas del sistema.
Interfaz de Usuario: Se utilizó un Layout simple con elementos de texto para informar el estado del servicio de monitoreo.

Integrantes del grupo
Villegas Maria Lourdes - DNI: 46332709
Milena Miselli - DNI: 44164036
