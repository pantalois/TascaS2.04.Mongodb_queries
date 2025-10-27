# Ejercicios de Consultas MongoDB: Colección "Restaurants"

## Descripción

Este proyecto documenta una serie de consultas (queries) avanzadas de MongoDB, diseñadas para practicar el filtrado de datos, el manejo de campos anidados (objetos, arrays) y la configuración de proyecciones. 
El objetivo es aplicar correctamente operadores lógicos, operadores de array (`$elemMatch`, `$type`) y gestionar la salida de resultados (`_id: 0`). Todas las consultas se basan en el dataset de ejemplo `restaurants`.

## Tecnologías Usadas

* **Base de Datos:** MongoDB
* **Entorno de Ejecución:** Mongo Shell (`mongosh` o el `mongo` shell heredado)

## Cómo Ejecutar las Consultas

1.  **Conexión:** Inicia Mongo Shell y conéctate a tu instancia de MongoDB donde residan los datos (ej. `mongosh "mongodb://localhost:27017"`).
2.  **Selección de DB:** Una vez conectado, selecciona la base de datos que contiene la colección `restaurants` usando el comando `use <nombre_de_la_db>`.
3.  **Ejecución:** Copia y pega cualquiera de las líneas de consulta directamente en la terminal de Mongo Shell y presiona Enter para ver los resultados.
