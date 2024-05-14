# Procesar un pago con izipay Checkout

Cree un formulario de pago simple y seguro para recopilar detalles de pago. 
Se incluyen algunos datos básicos para inicializar una transacción.

## Ejecutando el ejemplo

1. Instalar los paquetes

~~~
npm install
~~~

2. Ejecutar la aplicación

~~~
npm run server
abrir index.html con live-server o el servidor de su preferencia
~~~

3. Ir a: [http://{tu_server}/public/index.html](http://{tu_server}/public/index.html)

#### En caso de error en el archivo server.js verificar que los puertos configurados sean los mismos que proporciona el live-server

## Configuración del checkout -> "/src/pay.js":
1. Generación de Token de Sesión(GetTokenSession)
2. Visualizar el checkout - Llamar a LoadForm del SDK de izipay checkout