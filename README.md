<h1 align="center"> TFM_MI40_Raspberry PI </h1>
<h1 align="center"> ============================================= </h1>

Sistema de comprobación de conexiones diseñado por Ángel Rubio Calvo para el TFM del Máster Interniversitario en Industria 4.0


# Índice:

- [Descripción del proyecto](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#Sobre-el-proyecto)

- [Requisitos](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#Requisitos)

- [Tecnologías de comunicación](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#Sistemas_de_comunicación)
  - [MQTT](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#MQTT)
  - [OPCUA](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#OPUA)
  - [MODBUS](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#MODBUS)

- [Instalación](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#Instalación)

- [Licencia](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#Licencia))

- [Conclusiones](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40#Conclusiones)


# Sobre el proyecto

El objetivo de este simple programa es la comprobación y puesta en marcha de un sistema de comunicaciones en varias tecnologías. 
El sistema funcionará en una Raspberry PI y podrá ser conectado a cualquier hardware industrial con conexión MQTT, OPCUA o MODBUS.


# Requisitos:
-Raspberry PI / Dispositivo con sistema Linux.

-Dispositivo conectado a la misma red con navegador para visualizar el dashboard.

-Sistema con capacidad de conexión en cualquiera de de los métodos de comunicación para testeo.


# Sistemas de comunicación:
Los siguientes sistemas de comuncicación podrán ser testados con el mencionado software.

## MQTT
Descripción de interfaz.

## OPCUA
Descripción de interfaz.

## MODBUS
Descripción de interfaz.

# Instalación

Para comenzar con la instalación se deberá partir una Raspberry o un ordenador con sistema Linux. 

(Guía oficial Node-red -> https://nodered.org/docs/getting-started/raspberrypi#running-locally)

Tras la instalación de Node-red se pasaría a importar el proyecto y desplegar el dashboard.

**1.** Desde la consola de la Raspberry ejecutamos el siguiente comando para iniciar la descarga e instalación de Node-RED.

```bash <(curl -sL https://raw.githubusercontent.com/node-red/linux-installers/master/deb/update-nodejs-and-nodered)```

**2.** Aceptar la descarga e instalación:

![image](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40/assets/81623644/3725c6c3-123e-4133-8a2a-dab56f100124)

**3.** Proceso de instalación:

![image](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40/assets/81623644/f4263fe7-1bb7-428d-8046-fdf72483c891)

**4.** Una vez instalado nos indicará que se ha completado, así como varias recomendaciones a seguir para su configuración:

![image](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40/assets/81623644/5fc7a191-21af-4dd1-a1d6-235e26313462)

**5.** Una vez configurado el comando node-red-start inicia el servicio permitiendo acceder a la interfaz de node red:

![image](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40/assets/81623644/e0ccb135-45cc-431a-8473-3723d0f004cf)
![image](https://github.com/toqueroagrd/Comprobador-de-conexiones_MI40/assets/81623644/a2f2e99f-f956-4400-91b7-4bfd210b4387)

**6.** Como recomendación ejecutar node-red de forma automática al encender la Raspberry utilizando el siguiente comando:

```sudo systemctl enable nodered.service```

**7.** Importamos el proyecto desde github tomando el enlace de este repositorio
// Imagen de importación

# Licencia
El uso de este software es totalmente libre ya que se ha desarrollado con software libre y haciendo uso de los complementos desarrollados por la comunidad.

# Conclusiones
Gracias por la lectura completa del documento y espero que sea de ayuda y la aplicación haya cumplido sus espectativas.
