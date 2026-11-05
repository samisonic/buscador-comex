# Buscador de colores Comex (HTML + JavaScript)

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub (por ejemplo `buscador-comex`).
2. Sube `index.html` y `colores_comex.csv` a la raíz del repositorio.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**, selecciona `main` y `/ (root)`, y guarda.
5. Espera a que GitHub Pages publique el sitio. La URL será similar a `https://TU-USUARIO.github.io/buscador-comex/`.

No abras `index.html` directamente con `file://`: el navegador puede bloquear la carga del CSV. Usa GitHub Pages o un servidor local.

## Búsquedas
- Automática: código, nombre/familia, RGB (3 valores separados por coma) o CMYK (4 valores).
- También puedes seleccionar explícitamente Código, Nombre, RGB exacto, CMYK exacto o Familia.

La búsqueda RGB/CMYK es exacta. Los valores de reproducción son aproximados.
