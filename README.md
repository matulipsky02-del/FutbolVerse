# FútbolVerse ⚽

Mini juego web responsive para adivinar futbolistas con pistas, intentos y puntuación.

## Ejecutarlo en tu computadora
1. Descomprimí `futbolverse.zip`.
2. Abrí la carpeta `futbolverse`.
3. Hacé doble clic en `index.html`. Se abre en el navegador.

No requiere instalaciones ni claves API. El progreso del juego se guarda localmente en el navegador.

## Publicarlo gratis con GitHub Pages
1. Creá una cuenta en https://github.com/ si todavía no tenés.
2. Creá un repositorio nuevo llamado `futbolverse`.
3. Subí `index.html` al repositorio (arrastralo a la pantalla de carga de archivos y confirmá el commit).
4. Entrá en **Settings → Pages**.
5. En **Build and deployment**, elegí **Deploy from a branch**.
6. Seleccioná la rama `main` y la carpeta `/ (root)`, y guardá.
7. Esperá unos minutos. GitHub te mostrará la URL pública en la misma sección de Pages.

## Personalizar el juego
En `index.html`, buscá `const players = [` para editar o agregar futbolistas. Cada jugador tiene:
- `name`: nombre que se muestra al acertar.
- `aliases`: respuestas alternativas aceptadas.
- `country`: país.
- `position`: posición.
- `clubs`: clubes para la pista.
- `fact`: dato para la última pista y la respuesta.
- `difficulty`: etiqueta de dificultad.

## Importante
- Es un prototipo de un solo archivo; no hay cuentas ni ranking compartido entre personas todavía.
- La puntuación se guarda en el dispositivo/navegador, no en un servidor.
- Los datos y clubes de ejemplo son informativos y pueden quedar desactualizados.
- No uses escudos, fotos ni marcas oficiales sin comprobar los derechos de uso.
