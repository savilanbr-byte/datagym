# Entreno en Casa

App para retomar el ejercicio en casa con tapete, mancuernas, bandas elásticas y lazo.

- **Hoy:** la sesión del día para ir marcando, con anotaciones de peso, repeticiones y notas por ejercicio, y el calendario con tu progreso.
- **Plan:** cuatro sesiones (Día A, B, C y Sesión suave) que puedes editar.
- **Catálogo:** 61 ejercicios con imágenes, técnica y adaptación a casa.

Funciona sin conexión y se puede instalar en el celular como una app.

## Publicarla en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `entreno-en-casa`). Puede ser público.
2. Sube **el contenido** de esta carpeta a la raíz del repositorio: `index.html`, `sw.js`, `manifest.webmanifest` y las carpetas `fonts` e `icons`. Desde la web: *Add file → Upload files* y arrastra todo.
3. Ve a *Settings → Pages*. En *Build and deployment* elige *Deploy from a branch*, la rama `main` y la carpeta `/ (root)`. Guarda.
4. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/entreno-en-casa/`.

## Instalarla en el celular

- **Android (Chrome):** abre la dirección, toca el menú ⋮ y elige *Instalar app* o *Agregar a pantalla principal*.
- **iPhone (Safari):** abre la dirección, toca *Compartir* y elige *Agregar a inicio*.

Ábrela una vez con internet; después funciona sin conexión.

## Tus datos

- Todo se guarda **en el dispositivo**, dentro del navegador. No hay servidor ni cuenta.
- Cada dispositivo tiene sus propios datos: lo que marques en el celular no aparece en el computador.
- Usa **Respaldo de tus datos** (abajo en la pestaña Hoy) para descargar o copiar una copia y para importarla en otro dispositivo. Haz un respaldo de vez en cuando: si borras los datos del navegador, se pierde lo guardado.
- Para pasar lo que ya registraste en la versión de Claude: allí toca *Copiar respaldo*, pégalo en una nota o correo, y en esta versión usa *Importar respaldo*.

## Actualizar

Cuando cambies `index.html`, sube también `sw.js` con un nuevo valor de `CACHE` (por ejemplo `entreno-v6.4`) para que los celulares descarguen la versión nueva. La app se actualiza al abrirla con conexión.

## Créditos

- Imágenes de ejercicios: [Free Exercise DB](https://github.com/yuhonas/free-exercise-db), dominio público.
- Ícono: logo Forti-Beetle, de la autora de la app.
- Tipografías: Bungee y Courier Prime (SIL Open Font License), Permanent Marker (Apache License 2.0). Las licencias están en la carpeta `fonts`.
