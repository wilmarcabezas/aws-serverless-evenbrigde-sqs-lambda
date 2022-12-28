# AWS Serverless EventBridge & SQS with Lambda

Este repositorio es un ejemplo de cómo utilizar EventBridge y SQS junto con Lambda para crear una aplicación Serverless en AWS.

## ¿Qué es EventBridge?

EventBridge es un servicio de AWS que permite la comunicación entre aplicaciones y servicios de manera sencilla y confiable. Puedes utilizar EventBridge para enviar y recibir eventos entre aplicaciones de manera fácil y rápida.

Para más información sobre EventBridge, puedes consultar la [documentación oficial de AWS](https://aws.amazon.com/es/eventbridge/).

## ¿Qué es SQS?

SQS (Simple Queue Service) es un servicio de colas de mensajes de AWS que permite la entrega fiable de mensajes entre aplicaciones. Utilizando SQS, puedes crear colas de mensajes que permiten a tus aplicaciones enviar y recibir mensajes de manera asíncrona.

Para más información sobre SQS, puedes consultar la [documentación oficial de AWS](https://aws.amazon.com/es/sqs/).

## ¿Qué es Lambda?

Lambda es un servicio de AWS que permite ejecutar código sin tener que preocuparte por la infraestructura. Con Lambda, puedes crear aplicaciones y servicios que se ejecutan de manera automática cuando se disparan ciertos eventos.

Para más información sobre Lambda, puedes consultar la [documentación oficial de AWS](https://aws.amazon.com/es/lambda/).

:rocket: ¡Este repositorio es una excelente forma de empezar a trabajar con EventBridge, SQS y Lambda en AWS! :rocket:

## Ejemplo de uso

En este repositorio, se proporciona un ejemplo de cómo utilizar EventBridge y SQS junto con Lambda para crear una aplicación Serverless.

La aplicación consiste en una página web que permite a los usuarios enviar mensajes. Al enviar un mensaje, este se almacena en una cola de SQS y se envía un evento a EventBridge. Una vez que el evento es recibido por EventBridge, se activa una función de Lambda que procesa el mensaje y lo muestra en la página web.

Para probar la aplicación, puedes seguir los siguientes pasos:

1. Clona el repositorio en tu máquina
local: git clone https://github.com/wilmarcabezas/aws-serverless-evenbrigde-sqs-lambda.git
2. Accede al directorio del repositorio: cd aws-serverless-evenbrigde-sqs-lambda

Instala las dependencias necesarias: npm install
Inicia el servidor de desarrollo: npm start
Accede a la página web en tu navegador: http://localhost:3000
Una vez que la página web esté abierta en tu navegador, podrás enviar mensajes y ver cómo estos son procesados por Lambda y se muestran en la página.

:tada: ¡Felicidades! Ahora sabes cómo utilizar EventBridge, SQS y Lambda para crear una aplicación Serverless en AWS. :tada:

# Características adicionales
Además de proporcionar un ejemplo de cómo utilizar EventBridge, SQS y Lambda, este repositorio también incluye algunas características adicionales que pueden ser útiles:

Autenticación de usuarios: La aplicación utiliza Amazon Cognito para permitir que los usuarios se registren y accedan a la página web.
Almacenamiento de mensajes: Los mensajes enviados por los usuarios son almacenados en una base de datos DynamoDB para que puedan ser consultados posteriormente.
Integración con SNS: La aplicación también permite a los usuarios suscribirse a una lista de correo utilizando Amazon SNS.
Estas características adicionales pueden ser útiles para aquellos que quieran expandir el ejemplo y crear aplicaciones más complejas.

#Contribuciones
Este repositorio es un proyecto de código abierto y está disponible para cualquier persona que quiera contribuir. Si tienes ideas de cómo mejorar el ejemplo o quieres reportar un error, no dudes en abrir una issue o enviar un pull request.

:heart: ¡Gracias por utilizar este repositorio! :heart:
