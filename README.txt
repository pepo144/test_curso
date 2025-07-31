 prueba tecnica microservicios spring boot

> Atendiendo el reto Code Challenge 
> Se desarrolla un microservicio en spring boot usuando buenas practicas de diseño y codificaion, 
> como los principios SOLID el enfoque ATDD y diferentes frameworks y librerias para optimizar el trabajo. 
> Asi como la implementación de comunicación asincrona

## Para usar este repositorio
Este proyecto contiene tanto el codigo fuente como un jar listo apra su ejecucion, el codigo fuente 
es una aplicacion spring boot gestionada con maven, por lo cual podra clonarse como un proyecto o ejecutar la aplicacion usando el jar.
La palicacion es autocontenida, cuando se inicia crea una base de datos H2 en memoria.

La aplicacion cuenta con una interface grafica para ver la documentacion de la API y probar los diferentes endpoints.

Se ha desarrollado un set de preubas para validar las diferentes reglas de negocio, 
todas han sido probadas con exito, si alguna prueba falla la aplicacion no compila.

Todas las dependencias estan descritas en el fichero de configuracion de maven pom.xml

El puerto por defecto es el 8084 para evitar posibles conflictos

### Requisitos previos
java 8 o superior
navegador web
opcional 
git 
IDE de desarrollo
