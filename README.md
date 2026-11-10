# Rutina Balón y Fuerza (PWA)

## Publicar en GitHub Pages (una sola vez)
1. En github.com crea un repositorio nuevo (por ejemplo `rutina`), público.
2. Sube **todo el contenido de esta carpeta** (index.html, manifest.webmanifest, sw.js y la carpeta icons) con "Add file → Upload files".
3. Ve a **Settings → Pages**. En "Build and deployment" elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y guarda.
4. En 1–2 minutos tu app estará en `https://TU-USUARIO.github.io/rutina/`.

## Instalar en el teléfono
- **Android (Chrome):** abre el enlace → menú ⋮ → *Instalar app* / *Agregar a pantalla de inicio*.
- **iPhone (Safari):** abre el enlace → botón Compartir → *Agregar a pantalla de inicio*.

## Subir cambios después
1. Reemplaza `index.html` en el repositorio por la versión nueva (Add file → Upload files, o `git push`).
2. En `sw.js` cambia `const VERSION = 'v1'` a `'v2'`, `'v3'`, etc.
3. Abre la app con internet: se actualiza sola (a veces hay que cerrarla y abrirla una vez más).

## Notas
- El progreso y el historial se guardan en el teléfono donde usas la app; no se sincronizan entre dispositivos.
- Funciona sin internet después de la primera carga.
- La voz de la guía y la pantalla activa funcionan al abrirla como app o en el navegador.
