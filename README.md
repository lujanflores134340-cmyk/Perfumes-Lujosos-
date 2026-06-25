# Perfumes Lujosos — Landing de Perfumería de Lujo

Landing ecommerce premium (negro + dorado) con hero cinematográfico, categorías por aroma,
perfumes destacados, buscador, carrito lateral funcional y **checkout directo a WhatsApp**.

## Cómo verla
Abre `index.html` en cualquier navegador, o súbela a GitHub y activa **GitHub Pages**:

1. Crea un repositorio nuevo en GitHub y sube **todo el contenido de esta carpeta**
   (`index.html` + la carpeta `assets/`).
2. Ve a *Settings → Pages*.
3. En *Source* elige la rama `main` y carpeta `/ (root)`.
4. En 1–2 minutos tu web estará publicada en `https://TU-USUARIO.github.io/TU-REPO/`.

> Importante: sube también la carpeta `assets/` junto al `index.html`; contiene las
> imágenes de los perfumes destacados.

## Configurar tu WhatsApp
El botón **Finalizar compra** abre WhatsApp con el pedido ya redactado.
Por defecto usa un número de ejemplo. Para poner el tuyo, busca en `index.html` la línea:

```js
WHATSAPP = '595981123456';
```

y reemplázala por tu número con código de país, sin `+` ni espacios
(Paraguay = `595` + número sin el 0 inicial, ej. `0981 123 456` → `595981123456`).

## Imágenes de producto
Las tarjetas usan ilustraciones de frasco generadas. Puedes reemplazarlas por fotos reales
arrastrando una imagen sobre cada recuadro (queda guardada), o sustituyendo los archivos
dentro de `assets/cat/` y `assets/prod/`.
