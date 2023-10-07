REST API

Rest es una arquitectura de software
- escalablidad
- fiabilidad
- simplicidad
- visibilidad 
- portabilidad
- facil de modificar

fundamentos:
* recursos: todo es considerado un recurso (usuarios, objetos, etc), cada recurso se identifica con una URL 
* metodos: get, post, put, etc, definen las operaciones que se pueden realizar con los recursos 
* representaciones: los recursos pueden tener varias representaciones (json, xml, html) el cliente deria poder elegir de que manera ver los recursos
* stateles: el servidor no debria mantener un estado entre el cliente, el cliente debe enviar toda la informacion para procesar la request 
* interfaz uniforme
* separacion de conceptos: permite que cliente y servidor evolucionen de manera separada

un endpoint es un path a donde podemos acceder para recuperar cierta informacion 