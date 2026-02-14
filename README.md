Proyectos de Robótica con Arduino

Este repositorio contiene proyectos desarrollados durante el bachillerato en **Mecatrónica**, enfocados en robótica móvil, control de actuadores y comunicación inalámbrica. Los proyectos fueron realizados con fines académicos y de competencia, aplicando conocimientos de programación, electrónica y control.


Carro de Carreras Controlado por RF

Proyecto de **vehículo de carreras inalámbrico** desarrollado para una competencia, utilizando **Arduino**, módulos **nRF24L01** y control mediante **joystick**. El sistema prioriza una respuesta rápida, estabilidad en maniobras y control preciso de dirección.

El vehículo se controla a través de comunicación por radiofrecuencia entre un transmisor y un receptor. El receptor, instalado en el carro, interpreta las señales del joystick y ejecuta las acciones correspondientes sobre los motores DC y el servomotor de dirección.

La dirección se implementa mediante un **servomotor**, permitiendo giros más suaves y realistas en comparación con un sistema de giro diferencial. Para mejorar la estabilidad del vehículo, se evita repetir instrucciones consecutivas innecesarias, reduciendo vibraciones y cambios bruscos.

**Tecnologías utilizadas:**
- Arduino
- C++
- nRF24L01
- Motores DC
- Puente H
- Servomotor
- SPI, RF24 y Servo libraries

**Resultados:**
- Comunicación estable y de baja latencia
- Respuesta rápida a los comandos
- Buena maniobrabilidad durante la competencia


Robot Sumo Autónomo

Robot sumo autónomo desarrollado como proyecto personal, cuyo objetivo es detectar al oponente, mantenerse dentro del dohyo y ejecutar acciones de ataque y evasión de manera automática.

El sistema utiliza sensores de distancia y sensores de línea para identificar tanto la presencia del oponente como el borde del área de combate. A partir de estas lecturas, el robot toma decisiones de movimiento sin intervención humana.

El control se implementa mediante programación en **C++**, aplicando una lógica de control basada en estados como búsqueda, ataque, corrección de trayectoria y retroceso. El robot cuenta con tracción diferencial mediante motores DC.

**Tecnologías utilizadas:**
- Arduino
- C++
- Sensores infrarrojos y ultrasónicos
- Sensores de línea
- Motores DC
- Electrónica básica

**Resultados:**
- Operación autónoma
- Detección efectiva del oponente
- Prevención de salida del área de combate
- Limitación mecánica en fuerza de empuje


Robot Seguidor de Línea

Robot móvil diseñado para seguir una línea mediante **cinco sensores analógicos**, interpretando la posición relativa de la línea y ajustando la velocidad de los motores para corregir la trayectoria.

La lógica de control se basa en comparaciones de umbral y ajustes diferenciales de velocidad, permitiendo giros suaves y búsqueda activa de la línea cuando se pierde la referencia.

**Tecnologías utilizadas:**
- Arduino
- C++
- Sensores infrarrojos analógicos
- Motores DC
- Puente H

**Resultados:**
- Seguimiento estable de la línea
- Correcciones suaves de trayectoria
- Buen desempeño en trayectos con curvas


Aprendizajes Generales

- Programación estructurada en C++
- Integración de sensores y actuadores
- Control de motores DC y servomotores
- Comunicación inalámbrica RF
- Resolución de problemas en sistemas reales


Posibles Mejoras Futuras

- Implementación de control PID
- Optimización mecánica
- Integración de visión artificial
- Migración a ROS para simulación y control avanzado
- Desarrollo de sistemas autónomos más complejos

Multimedia
-[CARRO.zip](https://github.com/user-attachments/files/25060034/CARRO.zip)
-[Evidencia.zip](https://github.com/user-attachments/files/25309927/Evidencia.zip)

