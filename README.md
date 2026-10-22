# Valentine Cannon — Nivel 1 (HTML5)

Juego arcade 2D para navegador, con controles táctiles y de ratón.

## Probar en tu computadora
Abre `index.html` en un navegador moderno.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub, por ejemplo `valentine-cannon`.
2. Sube `index.html`, `README.md` y la carpeta completa `assets` a la raíz del repositorio. Es importante conservar los nombres y la estructura de los archivos.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
6. Espera a que GitHub Pages publique el sitio. La dirección tendrá el formato:
   `https://TU-USUARIO.github.io/valentine-cannon/`

## Insertar en Blogger
En la entrada o página de Blogger, cambia al modo HTML y pega, sustituyendo la URL por la dirección real de GitHub Pages:

```html
<div style="width:100%;max-width:960px;margin:auto;">
  <iframe
    src="https://TU-USUARIO.github.io/valentine-cannon/"
    title="Valentine Cannon — Nivel 1"
    width="960"
    height="540"
    style="width:100%;aspect-ratio:16/9;border:0;display:block;background:#25112f;"
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>
```

## Nota
Este es un prototipo inicial con arte ilustrado de referencia, un nivel, disparo con arrastre, física arcade sencilla, puntuación, reinicio y condición de victoria. La física es aproximada y puede necesitar ajustes para que todas las colisiones sean perfectas. Los recursos gráficos están en `assets/`.
