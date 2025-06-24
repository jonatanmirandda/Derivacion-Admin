# Landing WhatsApp Rotador (sin backend)

Este proyecto permite redirigir a números de WhatsApp rotados de forma equitativa desde un archivo JSON.

## ¿Cómo usar?

1. Edita el archivo `public/data.json` para agregar o quitar números.
2. Subí todo el contenido a un repositorio de GitHub.
3. Activá GitHub Pages desde la pestaña Settings > Pages.
4. Accede a tu landing en: `https://<usuario>.github.io/<repositorio>/public`

## Archivos

- `public/index.html`: Landing para usuarios.
- `public/data.json`: Números con campo `habilitado`.
- `admin.html`: Panel local para editar `data.json` y descargarlo.

