# Karol Rojas · Portafolio

Sitio web personal de Karol Rojas, diseñadora gráfica (diseño editorial, identidad de marca y cartelismo).
Es un sitio estático: un solo `index.html` con el CSS y el JavaScript dentro. No necesita instalar nada.

## Archivos

```
index.html     ← toda la página
img/           ← todas las imágenes (los nombres deben quedar iguales, en minúsculas)
.nojekyll      ← le dice a GitHub Pages que publique la carpeta tal cual
.gitignore     ← archivos que GitHub debe ignorar
README.md      ← este archivo
```

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `portafolio`).
2. Toca **Add file → Upload files** y arrastra **lo que está dentro** de la carpeta (`index.html`, `img`, `.nojekyll`, `.gitignore`, `README.md`), no la carpeta completa.
3. Toca **Commit changes**.
4. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Guarda.
5. En uno o dos minutos tu página estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Pendiente por completar

- **Imágenes:** las de `img/` son recortes provisionales de la captura de Figma. Para mejor calidad, exporta cada una desde Figma y reemplázala **con el mismo nombre** (`retrato.jpg`, `zobeida.jpg`, etc.).
- **Correo del formulario:** en `index.html`, al final, cambia `tu-correo@ejemplo.com` por tu correo real.
- **Behance y LinkedIn:** en el pie de página, reemplaza `https://www.behance.net/` y `https://www.linkedin.com/` por los enlaces a tus perfiles.
