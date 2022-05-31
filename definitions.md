# Golang con Microservicios

La arquitectura de microservicios es un patrón de diseño que estructura las aplicaciones como una colección de servicios. En un mundo impulsado por la computación en la nube, los microservicios se han convertido en uno de los patrones más populares de diseño de arquitectura. 

Las siguientes son algunas de las ventajas de los microservicios:

* Son fáciles de mantener y de poner a prueba.
* Poseen bajo acoplamiento, es decir, existe una independencia de los componentes entre si.
* Se despliegan independientemente.
* Se organizan con base a las capacidades del negocio.
* Son propiedad de un grupo pequeño de personas.

Los microservicios son fáciles de mantener/probar, se escalan más eficientemente, utilizan menos recursos y se enfocan en procesos específicos.

## Go Kit

Es un toolkit de programación para construir microservicios en Go. Fue creado para solucionar problemas comunes en sistemas distribuidos y aplicaciones, permitiendole a los desarrolladores enfocarse en la parte comercial de la programación. Es un grupo de paquetes relacionados que, en conjunto, crean un framework para construir grandes arquitecturas orientadas a servicios. 

Su principal capa de transporte es la Llamada de Procesamiento Remoto(RPC), pero también utiliza JSON por medio de HTTP y es fácil de integrar con los componentes de infraestructura más comunes, reduciendo la fricción de despliegue y promover la interoperabilidad con sistemas existentes.

## Bibliografía

* https://www.encora.com/es/blog/construyendo-microservicios-con-golang-y-go-kit