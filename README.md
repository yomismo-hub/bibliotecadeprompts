# Biblioteca de Prompt / Prompt Library

[Español](#español) · [English](#english)

---

## Español

Biblioteca personal de prompts organizada por **modelo de IA** y **categoría**. Funciona sin conexión, sin cuentas y sin suscripciones: son archivos Markdown normales más una página web autónoma. Aunque dejes de pagar cualquier servicio, tus prompts siguen siendo tuyos.

### Qué incluye

- `index.html`: la aplicación web. Un solo archivo, sin dependencias ni conexión a internet.
- `<Modelo>/<categoría>/*.md`: un archivo Markdown por prompt (46 de ejemplo).

**Modelos (23)**

| Grupo | Modelos |
|---|---|
| Texto | ChatGPT, Claude, Gemini, Microsoft Copilot, Perplexity, DeepSeek, Grok, Universal |
| Imagen | Midjourney, Stable Diffusion, Adobe Firefly, Ideogram, Leonardo.ai, FLUX |
| Vídeo | Seedance, Kling AI, Runway, MiniMax, Luma, Wan, Synthesia, Veo, Sora |

**Categorías:** imagen, vídeo, productividad, programación, escritura, análisis de datos, aprendizaje y otros. Cada modelo solo muestra las categorías que tiene (por ejemplo, Midjourney solo tiene *imagen* y Runway solo *vídeo*).

### Cómo empezar

1. **Descarga el proyecto** (botón verde *Code → Download ZIP*) y abre `index.html` con doble clic en tu navegador.
2. O, si el autor ha activado GitHub Pages, abre directamente la dirección pública del repositorio.

### Cómo se usa

- **Buscar:** escribe en el buscador; mira título, texto del prompt, etiquetas y notas.
- **Filtrar:** elige un modelo y, después, una categoría. Puedes ordenar por mejor valorados, más recientes o por título.
- **Usar:** el botón **Usar** abre un formulario con un campo por cada parte variable. Rellénalos y pulsa **Copiar** para obtener el prompt listo.
- **Copiar / Ver:** copia el prompt tal cual o ábrelo entero con su ejemplo de resultado y sus notas.
- **Valorar:** pulsa las estrellas (1 a 5) para marcar los que mejor funcionan.
- **Añadir:** **+ Añadir prompt** abre un formulario. Al guardar, se añade a tu biblioteca y se descarga su archivo `.md`.
- **Editar:** cambia un prompt y la versión sube sola si modificas el texto.
- **Borrar:** quita un prompt de la biblioteca del navegador (no toca tus archivos `.md`).

### Variables

Las partes que cambian se escriben entre **[CORCHETES]**, con un máximo de 40 caracteres, por ejemplo `[TEMA]` o `[TONO: formal o cercano]`. La web las resalta y las convierte en campos del formulario de **Usar**.

### Formato de cada archivo

```markdown
---
titulo: Revisión y mejora de código
modelo: Claude
categoria: programacion
etiquetas: [programacion, revision]
fecha: 2026-11-08
valoracion: 4
version: 1
---

## Prompt

Revisa este código en [LENGUAJE]: [CÓDIGO]. ...

## Ejemplo de resultado

Pega aquí un resultado real.

## Notas

- Cuándo funciona mejor y qué ajustar.
```

El nombre del archivo es `<categoría>-<titulo-en-minusculas>.md`, y va en la carpeta `<Modelo>/<categoría>/`.

### Tus datos y copias de seguridad

- Todo se guarda **solo en tu navegador** (almacenamiento local). No se envía nada a ningún servidor y la web no hace conexiones externas.
- Si borras los datos del navegador, se pierden los cambios hechos en la web. Para evitarlo:
  - **Descargar todo (.zip):** exporta tu biblioteca con la estructura de carpetas anterior.
  - **Importar .md / Importar carpeta:** carga archivos sueltos o la carpeta completa. Si un prompt ya existe (mismo modelo, categoría y título), se actualiza.
- Los archivos `.md` son la fuente de verdad: puedes guardarlos en Drive, Dropbox o en este repositorio.

### Añadir prompts al repositorio

Crea el prompt desde la web, descarga su `.md` y súbelo a la carpeta `<Modelo>/<categoría>/` (o abre una *pull request*). Si el modelo es nuevo, también hay que añadirlo en la lista `GRUPOS` al principio del script de `index.html`.

### Notas importantes

- Los prompts son **puntos de partida**. Las herramientas de IA cambian a menudo; revisa la guía oficial si algo deja de funcionar.
- Los prompts de imagen y vídeo están en inglés a propósito, porque la mayoría de esas herramientas responden mejor así.
- La sección *Notas* de cada prompt indica la guía oficial o pública en la que se basa.
- Los ejemplos se entregan sin resultados reales; el campo *Ejemplo de resultado* está para que lo rellenes tú.

---

## English

A personal prompt library organized by **AI model** and **category**. It works offline, with no accounts and no subscriptions: it is just plain Markdown files plus a self-contained web page. Even if you stop paying for any service, your prompts stay yours.

### What's inside

- `index.html`: the web app. A single file, with no dependencies and no internet connection needed.
- `<Model>/<category>/*.md`: one Markdown file per prompt (46 examples).

**Models (23)**

| Group | Models |
|---|---|
| Text | ChatGPT, Claude, Gemini, Microsoft Copilot, Perplexity, DeepSeek, Grok, Universal |
| Image | Midjourney, Stable Diffusion, Adobe Firefly, Ideogram, Leonardo.ai, FLUX |
| Video | Seedance, Kling AI, Runway, MiniMax, Luma, Wan, Synthesia, Veo, Sora |

**Categories:** image, video, productivity, programming, writing, data analysis, learning and other. Each model only shows the categories it actually has (for example, Midjourney only has *image* and Runway only *video*). The category names in the app and in folder names are in Spanish: `imagen`, `video`, `productividad`, `programacion`, `escritura`, `analisis-de-datos`, `aprendizaje`, `otros`.

### Getting started

1. **Download the project** (green *Code → Download ZIP* button) and double-click `index.html` to open it in your browser.
2. Or, if the author enabled GitHub Pages, open the repository's public address directly.

### How to use it

- **Search:** type in the search box; it looks at title, prompt text, tags and notes.
- **Filter:** pick a model, then a category. Sort by top rated, most recent or title.
- **Use:** the **Usar** (Use) button opens a form with one field for each variable part. Fill them in and press **Copiar** (Copy) to get the finished prompt.
- **Copy / View:** copy the prompt as is, or open it in full with its example result and notes.
- **Rate:** click the stars (1 to 5) to mark the ones that work best.
- **Add:** **+ Añadir prompt** (Add prompt) opens a form. When you save, it is added to your library and its `.md` file is downloaded.
- **Edit:** change a prompt; the version number goes up automatically if you change the text.
- **Delete:** removes a prompt from the browser library (it does not touch your `.md` files).

### Variables

The parts that change are written in **[SQUARE BRACKETS]**, up to 40 characters, for example `[TOPIC]` or `[TONE: formal or friendly]`. The app highlights them and turns them into fields in the **Use** form.

### File format

```markdown
---
titulo: Code review and improvement
modelo: Claude
categoria: programacion
etiquetas: [programming, review]
fecha: 2026-11-08
valoracion: 4
version: 1
---

## Prompt

Review this [LANGUAGE] code: [CODE]. ...

## Ejemplo de resultado

Paste a real result here.

## Notas

- When it works best and what to adjust.
```

The front matter keys are in Spanish (`titulo` = title, `modelo` = model, `categoria` = category, `etiquetas` = tags, `fecha` = date, `valoracion` = rating, `version` = version) and so are the section headings (`## Prompt`, `## Ejemplo de resultado` = example result, `## Notas` = notes), because the app reads them by those names. File names follow `<category>-<lowercase-title>.md` and live in `<Model>/<category>/`.

### Your data and backups

- Everything is stored **only in your browser** (local storage). Nothing is sent to any server and the app makes no external connections.
- If you clear your browser data, changes made in the app are lost. To avoid that:
  - **Descargar todo (.zip)** (Download all): exports your library with the folder structure above.
  - **Importar .md / Importar carpeta** (Import .md / Import folder): loads single files or the whole folder. If a prompt already exists (same model, category and title), it is updated.
- The `.md` files are the source of truth: keep them in Drive, Dropbox or in this repository.

### Adding prompts to the repository

Create the prompt in the app, download its `.md` and upload it to `<Model>/<category>/` (or open a pull request). If the model is new, also add it to the `GRUPOS` list at the top of the script in `index.html`.

### Good to know

- Prompts are **starting points**. AI tools change often; check the official guide if something stops working.
- Image and video prompts are in English on purpose, because most of those tools respond better that way.
- The *Notas* (Notes) section of each prompt lists the official or public guide it is based on.
- The examples ship without real results; the *Ejemplo de resultado* (Example result) field is for you to fill in.
