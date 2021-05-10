# Instrucciones

A continuación las instrucciones para ejecutar el proyecto

## Installation

- Tener instalado php, mysql, composer y npm
- bajar el repo de la siguiente ruta: https://github.com/javier2233/test-api--ogin.git
- realizar un 
```bash
composer install  
npm install
```
 para traer las librerías y paquetes necesarios

- se debe crear previamente una base de datos llamada "dbtest" y cambiar las credenciales de acceso de ser necesario en el archivo .env
- correr el comando 
```bash
php artisan migrate
```
para que genere las tablas necesarias

- correr el comando 
```bash
php artisan serve
```
para que genere un servidor, la url debería ser algo así http://127.0.0.1:8000/

- el archivo test.postaman_collection de postman tiene las dos consultas donde se hace la prueba del login y register via API