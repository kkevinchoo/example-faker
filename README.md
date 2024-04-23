# Generador de Datos de Productos para Base de Datos

Este script PHP utiliza Faker para generar datos ficticios de productos y los inserta en una base de datos MySQL.

## Requisitos

- PHP >= 7.0
- MySQL
- Biblioteca Faker de PHP

## Instalación

1. Clona o descarga este repositorio en tu máquina local.
2. Asegúrate de tener PHP y MySQL instalados en tu sistema.
3. Instala la biblioteca Faker de PHP ejecutando `composer install` en la raíz del proyecto.

## Configuración

1. Abre el archivo `generate_products.php`.
2. Configura los detalles de tu base de datos en las variables `$servername`, `$username`, `$password` y `$dbname`.
3. Reemplaza `'...'` en la variable `$json_data` con tu JSON de productos.

## Uso

1. Ejecuta el script `generate_products.php` desde la línea de comandos usando `php generate_products.php`.
2. Verifica la salida del script para asegurarte de que la tabla de productos se haya creado correctamente y los datos se hayan insertado en la base de datos.

## Contribución

Si encuentras algún error o tienes sugerencias de mejora, ¡no dudes en abrir un issue o enviar un pull request!

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).
