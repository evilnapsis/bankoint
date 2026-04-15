# Bankoint

Sistema de Gestión Bancaria/Puntos con PHP y MySQL.

## Descripción
Bankoint es una plataforma que permite a los clientes gestionar sus movimientos y a los administradores supervisar las operaciones del sistema.

## Estructura del Proyecto

El proyecto está dividido en dos módulos principales:

- **Módulo Cliente (`/`):** Sitio donde los clientes inician sesión para visualizar sus movimientos.
- **Módulo Administrador (`/administrator/`):** Panel de control para la gestión global del sistema.

### Organización de Archivos
- `administrator/core/app/view`: Vistas del módulo administrador.
- `administrator/core/app/action`: Acciones (lógica de procesamiento) del administrador.
- `administrator/core/app/model`: Modelos de base de datos (compartidos entre cliente y administrador).
- `core/app/layouts/layout.php`: Layout principal del sitio de clientes.

## Requisitos
- PHP 8.x o superior
- MySQL / MariaDB
- Servidor Web (Apache/Nginx)

## Instalación
1. Clonar el repositorio.
2. Importar el archivo `schema.sql` en su gestor de base de datos.
3. Configurar la conexión en `administrator/core/controller/Database.php`.
4. Acceder al sistema a través de su servidor local.

---
Desarrollado por [Evilnapsis](http://evilnapsis.com/) &copy; 2026