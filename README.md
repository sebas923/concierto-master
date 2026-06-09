# Sistema de Gestión y Venta de Entradas para Conciertos

## Descripción

Este proyecto es una aplicación web desarrollada en Laravel para la gestión y venta de entradas de conciertos. Permite administrar usuarios, realizar ventas de asientos, consultar reservas, generar tickets, enviar entradas por correo electrónico y gestionar recaudos de dinero.

El sistema está orientado a facilitar el proceso de reserva y control de entradas para eventos musicales, ofreciendo una interfaz tanto para clientes como para administradores.

---

## Objetivos del Proyecto

- Automatizar la venta de entradas para conciertos.
- Gestionar usuarios y roles dentro del sistema.
- Permitir la consulta de reservas realizadas.
- Generar y descargar tickets digitales.
- Enviar entradas al correo electrónico del cliente.
- Llevar control de recaudos y ventas realizadas.

---

## Tecnologías Utilizadas

### Backend
- PHP 8
- Laravel 8

### Frontend
- HTML5
- CSS3
- JavaScript

### Base de Datos
- MySQL

### Librerías y Dependencias
- Laravel Sanctum
- DomPDF
- Laravel Money
- Guzzle HTTP
- Milon Barcode
- Laravolt Avatar

---

## Funcionalidades Principales

### Clientes

- Reservar asientos para conciertos.
- Consultar reservas realizadas.
- Descargar tickets.
- Recibir tickets por correo electrónico.

### Administradores

- Iniciar sesión en el sistema.
- Gestionar usuarios.
- Registrar ventas.
- Consultar historial de ventas.
- Gestionar recaudos.
- Editar y eliminar usuarios.
- Administrar asientos vendidos.

---

## Estructura General del Proyecto

```text
app/
│
├── Http/
│   ├── Controllers/
│   ├── Middleware/
│
├── Models/
│
├── Policies/
│
└── Providers/

routes/
│
└── web.php

resources/
│
├── views/
│
public/

database/
