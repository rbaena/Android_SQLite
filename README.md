# Android_SQLite
SQLite en Aplicaciones Android

¿Qué es SQLite?

Es un ligero motor de bases de datos de código abierto, que se caracteriza por mantener el almacenamiento de información persistente de forma sencilla.  A diferencia de otros SGBD como MySQL, SQL Server, PostgreSQL y Oracle, SQLite tiene las siguientes ventajas:

•	No requiere el soporte de un servidor: SQLite no ejecuta un proceso para administrar la información, si no que implementa un conjunto de librerías encargadas de la gestión.
•	No necesita configuración: Libera al desarrollador de todo tipo de configuraciones de puertos, tamaños, ubicaciones, entre otros.
•	Usa un archivo para el esquema: Crea un archivo para el esquema completo de una base de datos, lo que permite ahorrarse preocupaciones de seguridad, ya que los datos de las aplicaciones Android no pueden ser accedidos por contextos externos.
•	Es de Código Abierto: Esta disponible al dominio público de los desarrolladores al igual que sus archivos de compilación e instrucciones de escalabilidad.
•	Es por eso que SQLite es una tecnología cómoda para los dispositivos móviles. Su simplicidad, rapidez y usabilididad permiten un desarrollo muy amigable.

SQLite tiene ciertas limitaciones en algunas operaciones. Por ejemplo, no se puede implementar las clausulas FULL OUTER JOIN y RIGHT OUTER JOIN. Aunque en la mayoría de casos esto no afectará, siempre habrá otras alternativas como MongoDB.

Ejemplo práctico:
Para comenzar a trabajar con SQLite en este documento se utilizar un ejemplo práctico.  Se trata de una aplicación llamada “Lo Célebre”. Cuyo objetivo es guardar una lista de frases célebres. 

