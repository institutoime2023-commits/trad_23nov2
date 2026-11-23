# TRADUCTOR Android V0.6 - Base de servicio en primer plano

Infraestructura inicial de servicio de primer plano para preparar la continuidad con pantalla bloqueada. En esta etapa la captura y el procesamiento todavía permanecen en MainActivity; no se considera lista para probar traducción en segundo plano.

## Base heredada



Aplicación Android con captura continua por ventana deslizante (4.0 s con superposición de 0.7 s), filtro de silencio RMS, optimización de contexto de audio en Whisper.cpp v1.7.6, traducción local con Google ML Kit y locución ordenada en español por auriculares/gafas Bluetooth.
