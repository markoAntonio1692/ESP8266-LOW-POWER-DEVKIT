# ESP8266-LOW-POWER-DEVKIT
ESP8266  LOW POWER DEVKIT
![](https://github.com/markoAntonio1692/ESP8266-LOW-POWER-DEVKIT/blob/master/Imagenes/frontal.JPG)

### Caracteristicas

- Diseñado para un ultrabajo consumo de energia.
- Ideal para aplicaciones con baterias de Ion de Litio 1S.
- Cuenta con un regulador de tension LDO TC1262 3.3V puede suministrar hasta 500mA.
- Incorpora un transistor mosfet canal N  en modo Drenador abierto (Drain open) conectado al Pin D8 (GPIO15), para activar o desativar circuitos con un maximo de corriente de 250mA.
- Boton de reset.
- Jumper para cambiar de  modo programacion a modo normal y viceversa.
- Jumper en el pin D0 a GND para modo "Deep Sleep"
- Programable con Ide Arduino.
- Compatible con pines de placa "Nodemcu".

# Cargar un Programa a ESP8266 DEVKIT LOW POWER
- Alimente a la placa ESP8266 DEVKIT LOW POWER por VIN.
- Coloque un Jumper entre los pin Heder "SW"

![](https://github.com/markoAntonio1692/ESP8266-LOW-POWER-DEVKIT/blob/master/Imagenes/vin.JPG)
- Cambie el Jumper a la posicion que se muestra en la imagen y reinicie, este cambio pondra a la esp8266 en modo programacion

![](https://github.com/markoAntonio1692/ESP8266-LOW-POWER-DEVKIT/blob/master/Imagenes/jumper.jpg)

- Utilice un Conversor UBS A Serial TTL como FTDI, CH340, CP210x, etc. Conectelo de esta forma. 

![](https://github.com/markoAntonio1692/ESP8266-LOW-POWER-DEVKIT/blob/master/Imagenes/serial.jpg)




