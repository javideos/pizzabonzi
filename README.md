# Pedidos Bonzi

Microapp de pedidos online de Pizza Bonzi. El cliente arma su pedido y lo envía por WhatsApp con el resumen listo.

Es un único archivo (`index.html`), sin instalación ni dependencias.

## Qué incluye

- Menú de Pizzas, Empanadas y Calzones con precios y descripciones.
- Tipo de masa (al molde / a la piedra) y observaciones por producto.
- Retiro en el local o envío a domicilio sin cargo, con propina sugerida de $1.000.
- Resumen del pedido enviado por WhatsApp.
- Horarios, dirección y estado "Abierto ahora / Cerrado ahora".

## Cómo editarlo

Todo está en `index.html`, dentro de la etiqueta `<script>`:

- `CONFIG`: nombre del local, número de WhatsApp y formas de pago.
- `MENU`: categorías, productos, descripciones y precios.

## Publicarlo con GitHub Pages

1. En el repositorio, entrá a **Settings > Pages**.
2. En **Source**, elegí **Deploy from a branch**.
3. Elegí la rama `main` y la carpeta `/ (root)`, y guardá.
4. En un par de minutos queda disponible en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
