# Documentación API - Registro de Usuarios

## Endpoint

`POST` a `registro.php`

## Parámetros requeridos:

- **usuario**: string, nombre de usuario.
- **contrasena**: string, contraseña del usuario.

## Respuestas posibles:

- `{"estado": "ok"}`: Registro exitoso
- `{"estado": "error", "mensaje": "Campos incompletos"}`: Faltan datos
