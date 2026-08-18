# JH-MAKER POS

Versión convertida a punto de venta.

## Flujo principal
1. `index.html`: caja POS, búsqueda, catálogo, carrito y administración básica de productos.
2. `scanner.html`: escáner de códigos de barras que agrega productos al mismo carrito.
3. `boletas.html`: generación y guardado de boletas en Firestore.
4. `historial.html`: consulta, descarga y anulación de boletas almacenadas.

Se eliminó el flujo/subweb de pedidos y envío por WhatsApp. El botón de cobro lleva directamente al generador de boletas.
