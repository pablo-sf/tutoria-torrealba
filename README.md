# Consulta de tutoría personal · Torrealba

Página para que el personal de Torrealba consulte desde el móvil el tutor personal de cada alumno. Se abre desde <https://www.torrealba.es/tutoria>.

Este repositorio **no contiene datos**. La página pide entrar con una cuenta de `torrealba.es` (aplicación interna de Google Cloud, así que Google no deja entrar a nadie de fuera) y lee con esa cuenta la hoja «Consulta de tutorías», compartida solo con el personal. Quien no tenga acceso a esa hoja no ve nada.

La hoja la crea y la mantiene el script del reparto, en un repositorio aparte y privado. `CONFIG` en `index.html` guarda el ID de cliente de Google y el de la hoja; ninguno de los dos es secreto.

Se publica con GitHub Pages desde la rama `main`: un `git push` basta para actualizarla.
