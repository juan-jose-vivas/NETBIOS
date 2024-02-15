# NETBIOS
NetBIOS es un protocolo de red que viene habilitado de forma predeterminada en Windows. Básicamente lo que permite NetBIOS es que las aplicaciones se comuniquen con la red
 Un equipo en una red local se comunica con otro a través de una conexión utilizando lo que se conoce como datagramas NetBIOS. Su función es establecer la sesión y mantener las conexiones. NetBIOS es un protocolo de capa de sesión, lo que significa que proporciona servicios para la capa de presentación y la capa de aplicación. NetBIOS se utiliza para proporcionar nombres de host y servicios a otras aplicaciones en una red. También se utiliza para compartir archivos e impresoras en una red local. Sin embargo, NetBIOS es un protocolo antiguo y obsoleto, y puede tener vulnerabilidades que son aprovechadas por los piratas informáticos para llevar a cabo diferentes métodos de ataques. Es posible desactivar NetBIOS en Windows siguiendo unos sencillos pasos.
**NetBIOS** (Network Basic Input/Output System) es un protocolo de red utilizado principalmente en sistemas operativos de Microsoft para proporcionar servicios de red en una red local. Fue desarrollado en la década de 1980 y, aunque ha sido en gran medida reemplazado por tecnologías más modernas, todavía juega un papel en ciertos entornos.
Aquí tienes una descripción detallada de NetBIOS:
**1. Función Principal:**
NetBIOS se diseñó originalmente para proporcionar una capa de abstracción sobre la comunicación entre dispositivos en una red local. Permite a los dispositivos descubrirse mutuamente y compartir recursos, como impresoras y archivos.
**2. Nombres NetBIOS:**
Uno de los conceptos fundamentales en NetBIOS es el sistema de nombres. Cada dispositivo en una red NetBIOS tiene un nombre de 16 caracteres que lo identifica. Estos nombres son utilizados para identificar recursos y para comunicarse entre dispositivos.
**3. Resolución de Nombres:**
Para que los dispositivos puedan comunicarse entre sí, necesitan saber la dirección IP correspondiente al nombre NetBIOS. El proceso de traducir un nombre NetBIOS a una dirección IP se llama resolución de nombres. NetBIOS proporciona dos métodos principales para resolver nombres:
- **Broadcast:** En una red local pequeña, un dispositivo puede enviar una transmisión de difusión preguntando por una dirección IP asociada a un nombre NetBIOS específico. Sin embargo, esto puede generar tráfico innecesario en redes más grandes.
- **WINS (Windows Internet Name Service):** WINS es un servicio centralizado que mantiene una base de datos de nombres NetBIOS y sus direcciones IP correspondientes. Los dispositivos pueden consultar el servidor WINS para obtener la dirección IP de un nombre NetBIOS.
**4. Sesiones y Comunicación:**
NetBIOS también maneja la creación y el cierre de sesiones entre dispositivos. Una sesión NetBIOS permite que dos dispositivos se comuniquen de manera confiable y bidireccional. Los datos enviados a través de una sesión NetBIOS están garantizados de llegar en el mismo orden en que se enviaron.
**5. Puertos NetBIOS:**
NetBIOS utiliza una serie de puertos para diferentes tipos de servicios. Por ejemplo:
- **Puerto 137:** Para el servicio de resolución de nombres NetBIOS (NBNS).
- **Puerto 138:** Para el servicio de datagramas NetBIOS (NBDGM), que maneja la comunicación sin conexión.
- **Puerto 139:** Para el servicio de sesión NetBIOS (NBSS), que maneja la comunicación orientada a la conexión.
**6. Seguridad y Limitaciones:**
NetBIOS fue desarrollado en una época en la que la seguridad en la red no era una preocupación tan importante como en la actualidad. Por lo tanto, NetBIOS carece de muchas características de seguridad modernas y puede ser vulnerable a ataques. Por esta razón, se recomienda encarecidamente su uso solo en redes seguras y protegidas.
En resumen, NetBIOS es un protocolo de red obsoleto pero que aún puede encontrarse en entornos de red heredados o en configuraciones específicas. Aunque ha sido en gran parte reemplazado por tecnologías más seguras y eficientes, como TCP/IP y DNS, es importante comprender NetBIOS para trabajar con sistemas y redes más antiguos.
