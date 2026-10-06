Sistemas Digitales - Práctica Nro. 001

Uso de Wokwi y Microchip Studio en microcontroladores AVR: arquitectura, puertos de E/S y operaciones a nivel de bit

Este directorio contiene los archivos fuente, simulaciones y la documentación correspondiente a la primera actividad práctico-experimental (APE1) de la asignatura de Sistemas Digitales de la Carrera de Computación (Universidad Nacional de Loja).

🎯 Objetivo General

Reconocer la arquitectura del microcontrolador ATmega328P (Arduino UNO) y controlar sus periféricos de entradas/salidas digitales escribiendo y leyendo directamente sus registros mediante operaciones a nivel de bit, usando simulación en Wokwi y Microchip Studio.

👥 Nombre

Miguel Veintimilla

📂 Estructura del Repositorio

Los archivos .zip contienen el código (sketch.ino) y la configuración del circuito (diagram.json) de cada etapa de la práctica para ser ejecutados en el simulador.

A3.zip: Configuración inicial y reconocimiento del entorno.

B1.zip / B2.zip / B3.zip: Ejercicios de control de salidas digitales (LEDs). Se configuran y manipulan los registros DDRx, PORTx y PINx utilizando máscaras (AND, OR, XOR, NOT) y desplazamientos de bits (<<, >>).

C2.zip: Laboratorio de bits y lectura de entradas. Implementación de lógicas combinadas y lectura del estado de un pulsador usando resistencias pull-up internas.

D1.zip: Benchmarking (Pruebas de rendimiento). Comparación del tiempo de ejecución entre el acceso mediante la API nativa de Arduino (digitalWrite) y el acceso directo a los registros en tiempo de ejecución.

main.c: Código fuente en C utilizado para el análisis de compilación y revisión del código ensamblador generado (Instrucciones AVR como SBI, CBI, IN, OUT, etc.).

APE1_Miguel_Veintimilla.pdf: Reporte técnico completo con capturas de pantalla, enlaces a las simulaciones en vivo, tablas de correspondencia de ensamblador, análisis teórico y conclusiones.

🛠️ Herramientas y Tecnologías

Plataforma de Simulación: Wokwi

Entorno de Análisis: Microchip Studio 7 / Compiler Explorer

Hardware Target: Arduino UNO (ATmega328P a 16 MHz)

Lenguaje: C / C++ (Bare-metal y API Arduino)

🚀 Cómo visualizar las simulaciones

Para ejecutar cualquiera de los ejercicios:

Descarga el archivo .zip correspondiente (ej. B1.zip).

Descomprime los archivos en tu computadora.

Ve a Wokwi, crea un nuevo proyecto de Arduino UNO y reemplaza los archivos por defecto con el sketch.ino y el diagram.json extraídos.

Inicia la simulación.

Nota: Alternativamente, puedes consultar el documento PDF adjunto, el cual contiene los enlaces web directos a cada simulación guardada en la nube.
