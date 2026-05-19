# INF781-Laravel2FA

Sistema de autenticación en dos factores (2FA) desarrollado en Laravel 13 utilizando Google Authenticator y PostgreSQL.

## Requisitos

- PHP 8.4
- Composer
- Node.js
- PostgreSQL
- Laravel 13

## Instalación

Clonar repositorio:

```bash
git clone URL_DEL_REPOSITORIO
```

Ingresar al proyecto:

```bash
cd INF781-Laravel2FA
```

Instalar dependencias PHP:

```bash
composer install
```

Instalar dependencias Node:

```bash
npm install
```

Configurar variables de entorno:

```bash
cp .env.example .env
```

Generar clave:

```bash
php artisan key:generate
```

Ejecutar migraciones:

```bash
php artisan migrate
```

Compilar assets:

```bash
npm run build
```

Iniciar servidor:

```bash
php artisan serve
```

## Funcionalidades

- Registro e inicio de sesión
- Middleware de autenticación
- Autenticación en dos factores (2FA)
- QR dinámico
- OTP/TOTP con Google Authenticator

## Autor

Mauren Fernanda Villca Salas
Carrera de Ingeniería Informática
UATF