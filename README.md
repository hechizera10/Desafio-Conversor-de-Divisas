Challenge Cinco de Seis | Formación Java Orientado a Objetos | Conversor de Moneda

<h1 align="center">:currency_exchange: Conversor de Moneda ☕</h1>


En este desafio realicé un conversor de moneda utilizando como moneda base el Peso Mexicano, el conversor
obtiene los valores del peso mexicano frente a las divisas extranjeras solicitadas.

La aplicación debe estar conectada a internet, ya que consume dos API REST las cuales son Exchange Rates Data API y del Sistema de Información Económica (SIE) API del Banco de México.

Los valores más actualizados provienen de Exchange Rates Data API, mientras que los valores del SIE API del BAnco de México son de forma mensual.

Incluye también un conversor de temperaturas, este puede usarse sin conexión a internet.

Extra personal:
- Imágenes de fondo personalizados en Canva.com

**Tecnologías 💻:**

   - Java SE 8 U331 ☕
            
         - Interfaz gráfica desarrollada con Javax.Swing.
         - Uso de Programación Orientada a Objetos.
         - Cálculos de conversión realizados y manejo de cifras monetarias con la clase BigDecimal.
  




**Instrucciones para ejecución:**

  - Una vez descargado, descomprima.
  - Abra la carpeta dist.
  - Ejecute el archivo conversor-moneda con extensión JAR.
  - **¡Importante!** El archivo JAR debe permanecer dentro del directorio dist ya que este posee las librerías utiliadas en el directorio lib.
  - Asegurese de estar conectado a internet al utilizar el conversor de moneda.

Públicado en el topic:

https://github.com/topics/challengeoneconversorlatam


**Librerías 📖:**
   
   - ![JAR](https://img.shields.io/badge/OkHttp--3.0.0--RC1-JAR-blue) <a href="https://repo1.maven.org/maven2/com/squareup/okhttp3/okhttp/3.0.0-RC1/okhttp-3.0.0-RC1.jar">Okhttp 3.0.0-RC1</a>
   - ![JAR](https://img.shields.io/badge/Okio--1.12.0-JAR-blue) <a href="https://repo1.maven.org/maven2/com/squareup/okio/okio/1.12.0/okio-1.12.0.jar">Okio-1.12.0</a>
   - ![JAR](https://img.shields.io/badge/JSON--In--Java--20220320-JAR-blue) <a href="https://repo1.maven.org/maven2/org/json/json/20220320/json-20220320.jar">JSON In Java-20220320</a>




**Requisitos Proyecto:**

El convertidor de moneda debe:

           - Convertir de la moneda de tu país a Dólar
           - Convertir de la moneda de tu país  a Euros
           - Convertir de la moneda de tu país  a Libras Esterlinas
           - Convertir de la moneda de tu país  a Yen Japonés
           - Convertir de la moneda de tu país  a Won sul-coreano

Recordando que también debe ser posible convertir inversamente, es decir:

           - Convertir de Dólar a la moneda de tu país
           - Convertir de Euros a la moneda de tu país
           - Convertir de Libras Esterlinas a la moneda de tu país
           - Convertir de Yen Japonés a la moneda de tu país
           - Convertir de Won sul-coreano a la moneda de tu país

**Extras:**
Como desafío extra te animamos a que dejes fluir tu creatividad, si puedo convertir divisas, ¿tal vez pueda añadir a mi programa otros tipos de conversiones como temperatura por ejemplo?
