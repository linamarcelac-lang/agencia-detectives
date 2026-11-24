# 🦉 Agencia de Detectives · AVA

Proyecto ABP **«Detectives de nuestra comunidad»**, de grado 3.º en el Colegio San José de las Vegas. Integra Lengua Castellana y Ciencias Sociales durante 11 semanas, en 6 fases (expedientes).

> **Gran pregunta:** ¿Cómo podríamos mejorar la convivencia en los espacios que compartimos en nuestro colegio para que todos nos sintamos respetados, escuchados y cuidados?

## Contenido del repositorio

| Archivo | Qué es |
|---|---|
| `index.html` | La Agencia de Detectives: portada, 6 expedientes y la pestaña «Clases del docente». |
| `juego-semana1.html` | Juego «El misterio del mensaje perdido» sobre emisor, receptor, mensaje y canal. Incluye Misión individual, Arena de la clase y Carrera de equipos. |
| `recursos/olivia-para-que-sirve.html` | Olivia explica con su voz el campo «¿Para qué sirve?» del AVA. |
| `.nojekyll` | Hace que GitHub Pages publique los archivos tal como están. |

Cada página es un solo archivo HTML que no necesita servidor ni base de datos. El progreso de los estudiantes se guarda en el navegador de cada equipo.

## Publicar con GitHub Pages

1. Cree un repositorio nuevo en GitHub, por ejemplo `agencia-detectives`, y márquelo como **Public**.
2. Toque **Add file → Upload files**, arrastre todo el contenido de esta carpeta, incluida la carpeta `recursos`, y luego toque **Commit changes**.
3. Vaya a **Settings → Pages**. En *Source* elija **Deploy from a branch**, la rama **main** y la carpeta **/ (root)**, y toque **Save**.
4. Después de 1 o 2 minutos, el sitio queda en:
   - Agencia: `https://SU-USUARIO.github.io/agencia-detectives/`
   - Juego: `https://SU-USUARIO.github.io/agencia-detectives/juego-semana1.html`
   - Olivia: `https://SU-USUARIO.github.io/agencia-detectives/recursos/olivia-para-que-sirve.html`

## Usarlo en Moodle

**Como recurso URL:** use *Añadir una actividad o recurso → URL* y pegue el enlace de la Agencia.

**Dentro de un campo de texto:** abra la vista de código `</>` y pegue lo siguiente. GitHub Pages sí permite mostrar sus páginas dentro de otro sitio.

```html
<iframe src="https://SU-USUARIO.github.io/agencia-detectives/recursos/olivia-para-que-sirve.html"
        width="100%" height="640" style="border:0;border-radius:16px;max-width:100%;"
        allow="autoplay" title="Olivia te cuenta para qué sirve"></iframe>
```

Para mostrar toda la Agencia dentro del campo, use el mismo código con el enlace de `index.html` y una altura de `height="800"`.

## Actualizar

Para cambiar algo, suba la nueva versión del archivo con el **mismo nombre**. GitHub reemplaza el archivo anterior y los enlaces del AVA siguen funcionando.
