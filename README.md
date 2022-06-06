# Almacenamiento en caché con Node.js y Redis
## ¿Qué es el caché y cómo puede ayudarnos?

La caché es el proceso con el que los datos se almacenan temporalmente en un área de componentes de almacenamiento para poder ser utilizados en el futuro con mayor rapidez. Por ej.. Si tenemos algunos datos que provienen de una API de terceros

## ¿Qué es Redis?

Redis es una base de datos NoSQL de código abierto y tiene un alto rendimiento que se utiliza principalmente como solución de almacenamiento en caché para varios tipos de aplicaciones. Almacena todos sus datos en RAM y promete lecturas y escrituras de datos altamente optimizadas.

## Ejemplo
- Instalar redis, en mi caso lo levanto desde Docker.

   **Comando:** run -p 6379-6379 -name some-redis -d redis
   
- Instalar el módulo **redis** para poder conectarme a redis, después instalo **express** para poder crear un servidor básico, un módulo **response-time** para medir el tiempo de respuesta y por último instalo **nodemon**.

   **Comando:** npm i redis express response-time nodemon

- Realizamos una petición con el módulo axios.
