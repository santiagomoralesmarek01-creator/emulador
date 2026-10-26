# Emulador móvil

Pegá un link o dominio y mirá cómo se ve ese sitio en un celular: iPhone, Pixel, Galaxy o iPad mini, al ancho real de cada pantalla.

- Girar a horizontal, recargar, abrir en pestaña nueva, zoom y modo claro/oscuro.
- Recuerda los últimos links y el último dispositivo elegido.
- Se puede compartir una vista directa con `?url=`, por ejemplo `/?url=ejemplo.com`.

Algunos sitios (Google, Instagram, bancos…) no permiten mostrarse dentro de otra página; para esos está el botón de abrir aparte.

## Uso local

Es un sitio estático, sin build:

```sh
python3 -m http.server
```

y abrir `http://localhost:8000`.

## Publicar en Vercel

Add New → Project → elegir este repositorio → Deploy. No necesita configuración.
