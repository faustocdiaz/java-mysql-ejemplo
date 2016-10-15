# Conectando aplicación Java a Mysql
Ejemplo del post https://hablandojava.blogspot.com/2016/10/conectar-java-mysql.html para conectarnos a una base de datos Mysql haciendo uso de una conexión simple de JDBC, el objetivo del ejemplo es lograr establecer la conexión para obtener del servidor de base de datos la fecha.

Introducción: Hola amigos, en este post estaré compartiendo un ejemplo de cómo conectar una aplicación Java a una base de datos Mysql.

Entorno Requerido: Eclipse Neon IDE y Mysql 5.7.15, for Linux (x86_64) 

El procedimiento lo puedes consultar directamente en 
https://hablandojava.blogspot.com/2016/10/conectar-java-mysql.html 

# Resúmen

Gracias a la interfaz que provee Java para establecer conexiones a bases de datos, hoy en día resulta muy sencillo consumir información que se encuentre en repositorios de datos de todo tipo, ya sea Oracle, Mysql, Postgresql, Microsoft Sql Server entre otras.  La interfaz que brinda Java para consumir la información de bases de datos se conoce como Java Database Conectivity o JDBC y la misma permite utilizar una forma estándar de acceso a bases de datos, lo que hemos realizado hasta ahora en este post ha sido gracias a esta interfaz.

Podemos concluir que Java brinda grandes beneficios para establecer conexiones a base de datos sobre todo cuando hacemos uso de las propiedades de conexión para que no sean fijadas en el mismo código fuente sino en un archivo de texto independiente del código fuente.  Una de las mejores prácticas que podemos seguir cuando nos conectamos a una base de datos es siempre dejar configurada la ruta de acceso o credenciales fuera de nuestro código, esto con el fin de que el mantenimiento del sistema sea menos costoso.
