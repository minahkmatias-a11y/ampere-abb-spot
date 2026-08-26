# Si Tiene Enchufe — Propuesta Ampere × ABB E-mobility

Propuesta de spot publicitario para el cargador domiciliario ABB comercializado por Ampere. Sitio de una sola página (`index.html`, autocontenido, sin dependencias externas más que Google Fonts) con las siguientes secciones en pestañas:

- Presentación
- Idea y objetivo
- Referencias
- Casting
- Guión
- Cronograma

## Publicar en GitHub Pages

1. Creá un repositorio nuevo en GitHub (puede ser público o privado; Pages funciona en ambos si tenés plan que lo permita).
2. Desde esta carpeta, corré:

   ```bash
   git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
   git branch -M main
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Source → Deploy from a branch**, elegí la rama `main` y la carpeta `/ (root)`. Guardá.
4. En un par de minutos el sitio queda publicado en `https://<tu-usuario>.github.io/<tu-repo>/`.

## Actualizar el sitio más adelante

Reemplazá `index.html` por la versión nueva y corré:

```bash
git add index.html
git commit -m "Actualiza propuesta"
git push
```
