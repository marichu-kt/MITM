
# Wireshark - Herramienta de Intercepción de Tráfico en Tiempo Real 🔒

![MITM](/Images/icon.png)

Descripción:
------------
Wireshark es una herramienta de código abierto diseñada para realizar análisis
de tráfico en tiempo real. Esta herramienta permite a los usuarios capturar y 
examinar el tráfico de red en detalle, lo que puede ser útil para diagnosticar 
problemas de red, detectar intrusiones y entender el funcionamiento de los 
protocolos de red.

Características:
----------------
- 🛡️ Captura y analiza el tráfico de red en tiempo real.
- 🔄 Permite el análisis detallado de paquetes de datos.
- 🔑 Puede mostrar contraseñas y datos confidenciales si no se utiliza en un entorno seguro.
- 📶 Soporta una amplia gama de protocolos de red como HTTP, HTTPS, FTP, etc.
- 🖥️ Funciona en múltiples plataformas: Windows, macOS y Linux.
- 📊 Proporciona estadísticas detalladas sobre el tráfico de red.

Instalación:
-------------
1. Descarga Wireshark desde wireshark.org.  o con: `sudo apt install wireshark`
2. Sigue las instrucciones de instalación para tu sistema operativo.
3. Ejecuta Wireshark desde el menú de aplicaciones.

Uso:
-----
- Abre Wireshark y selecciona la interfaz de red que deseas monitorear.
- Observa el tráfico en tiempo real y utiliza las herramientas de filtrado y 
     análisis para examinar paquetes específicos.


¡Disfruta del análisis de tráfico con Wireshark! 😉

#
#

# Instrucciones para sniffear el trafico con Wireshark 🦈
Este repositorio contiene instrucciones para simular el registro de un usuario en Vulnweb utilizando Wireshark para analizar el tráfico de red.

## Requisitos previos 🛠️
- Wireshark instalado en el sistema.
- Acceso a internet para acceder a la página web de Vulnweb.

## Abra Wireshark en su sistema 🛜
Seleccione la interfaz de red adecuada (en este caso, "eth0" para Ethernet).

## Acceda a la página web de [Vulnweb](http://www.vulnweb.com/).
Diríjase al apartado de "Sign Up" para simular el registro de un nombre de usuario y contraseña.
Complete el proceso de registro como lo haría normalmente.

## Una vez completado el registro en Vulnweb, vuelva a Wireshark 🔍
Detenga el análisis de tráfico haciendo clic en el botón cuadrado arriba en la barra de herramientas.
En la barra de búsqueda, filtre los registros HTTP.
Haga clic en el registro correspondiente al registro en Vulnweb.
Seleccione "HTML from URL encoded" para ver los datos de usuario y contraseña capturados.
Se mostrarán el nombre de usuario ("uname") y la contraseña ("pass") capturados en el tráfico de red.

![Wireshark](/Images/img-1.png)


