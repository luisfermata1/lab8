# Programación Web
En la informática nos referimos a un CRUD como el modelo de un API capaz de crear, leer, actualizar y eliminar. Es por ello que en este proyecto tiene como objetivo realizar un CRUD completo para poder realizar pedidos de productos Apple, el tema es por gusto propio.

## Requisitos:
- Editor de texto a tu elección (VScode)
- Instalar NodeJs
- Instalar npm package manager

## Docker Compose:
Para poder levantar este proyecto es muy simple, ya que cuenta con un Docker compone que crea y levanta las imágenes y contenedores necesarios para el funcionamiento del CRUD completo. Debes tomar en cuenta las observaciones que se encuentran en este documento antes de seguir con estos pasos. 
Solo debes ejecutar el siguiente comando para crear la imagines:

```docker-compose buil```

luego estamos listos para correr la aplicación con:

```docker-compose up```

## Observaciones:
Para que este proyecto pueda correr localmente en tu maquina debes tomar en cuenta lo siguoente:
### Back-End:
En el ```api.js``` deberas editar los host ```redisdns.westus.azurecontainer.io``` y ```mongodns.westus.azurecontainer.io``` por: ```localhost``` para que estos puedan redireccionar localmente en tu maquina.
### Front-End:
Existe un  ```pedido.service.ts``` deberas editar el host ```appidns.westus.azurecontainer.io``` por: ```localhost``` para que estos puedan redireccionar localmente en tu maquina.
