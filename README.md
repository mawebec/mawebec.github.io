# Sitio web de MaGames (GitHub Pages, gratis)

Google Play pide una URL pública para la política de privacidad, y AdMob pide un
archivo `app-ads.txt` en la raíz del sitio del desarrollador. GitHub Pages
resuelve las dos cosas gratis.

## Pasos (una sola vez, ~10 minutos)

1. Crear una cuenta en https://github.com si no tienes.
2. Crear un repositorio **público** llamado exactamente `<tu-usuario>.github.io`
   (por ejemplo, si tu usuario es `magames`, el repo se llama `magames.github.io`).
3. Subir **todo el contenido** de esta carpeta (`index.html`, `privacy.html`,
   `app-ads.txt` y las carpetas `img/` y `fonts/`; este README no hace falta)
   con *Add file → Upload files*, arrastrar y *Commit changes*.
4. En el repo: *Settings → Pages* → Source: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
5. En 1–2 minutos queda en línea:
   - Sitio: `https://<tu-usuario>.github.io`
   - Política: `https://<tu-usuario>.github.io/privacy.html`
   - app-ads: `https://<tu-usuario>.github.io/app-ads.txt`

El correo de contacto (mawebec@gmail.com) ya está puesto en `privacy.html`.
En Play Console, el "sitio web del desarrollador" tiene que ser exactamente
`https://<tu-usuario>.github.io` para que AdMob encuentre el `app-ads.txt`.
