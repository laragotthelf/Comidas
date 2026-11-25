# 🛒 Mi cocina

Planificador semanal de comidas, recetas, inventario y lista de compras, todo conectado. Funciona en celular y computadora, con modo claro/oscuro.

Es una app de un solo archivo (HTML + JS + CSS), sin dependencias ni build. Los datos se guardan en el navegador (`localStorage`) de cada dispositivo.

## Publicar con GitHub Pages
1. Subí todos los archivos de esta carpeta a la raíz de tu repositorio.
2. En GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
3. Tu app quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
4. En el celular, abrí ese link y elegí "Agregar a pantalla de inicio" para instalarla con el logo.

## Estructura
- `index.html`: la aplicación completa
- `manifest.json`: datos para instalarla como app
- `icons/`: logo (SVG y PNG)

## Reglas principales
Planificar no descuenta stock; solo se descuenta al marcar una comida como realizada (con confirmación y opción de deshacer). La lista de compras = necesidades de las comidas pendientes − stock físico + productos manuales.
