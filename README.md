# Titi

Tu vida en un solo lugar: tareas, universidad, estudio, contabilidad, hábitos, notas y metas, con un asistente de voz llamado **Titi**.
Una sola página, sin cuentas, sin servidores y **funciona sin internet**.

Diseñado por [Jhordy Cabascango](https://www.tiktok.com/@jhordycabascango21)

## Reto Prime y hábitos medibles (versión 2.1)

- **Reto Prime:** en Inicio u Hábitos toca **Empezar mi reto** y elige 21, 30, 60 o 90 días. Un día cuenta si cumples el porcentaje de hábitos que elegiste (por ejemplo 80%). Verás el día en que vas, tu racha y un mapa de todos los días.
- **Hábitos Prime:** agrega agua, guineos, día sin azúcar, inglés, repaso, calistenia y flexibilidad. Si ya tienes uno parecido, lo vuelve medible **sin perder tu racha**.
- **Contadores y minutos:** al crear un hábito elige *Contar* (vasos, guineos…) o *Minutos al día*. Toca **+** y la barra avanza; al llegar a la meta queda hecho.
- **Cierre del día:** desde las 5 de la tarde, 2 minutos para anotar cómo te fue, qué hiciste bien, qué falló y qué harás mañana. Al final de la semana aparece tu resumen.
- **Modo simple:** en Ajustes. Deja Inicio solo con lo de hoy; no borra nada.
- Categorías de ingreso (banco, efectivo, mesada…) y NRC de cada materia.

**Actualizar sin perder datos:** sube estos archivos al mismo repositorio reemplazando los anteriores. Tus datos viven en el navegador de cada dispositivo y esta versión los respeta: los campos nuevos se agregan solos. Antes, por si acaso: Ajustes → Descargar respaldo.

## Subirlo a GitHub Pages (5 minutos)

1. Entra a <https://github.com> → **New repository** → nombre, por ejemplo `titi` → **Public** → **Create repository**.
2. Pulsa **uploading an existing file** y arrastra **todo** esto (incluida la carpeta `icons`):
   `index.html`, `sw.js`, `manifest.webmanifest`, `README.md` y la carpeta `icons/`.
   Luego **Commit changes**.
3. Ve a **Settings → Pages**. En *Build and deployment* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** → **Save**.
4. Espera 1–2 minutos. Tu app estará en `https://TU-USUARIO.github.io/titi/`.

## Instalarla en el celular / PC

- **Android (Chrome):** menú ⋮ → *Instalar app* / *Añadir a pantalla de inicio*.
- **iPhone (Safari):** botón Compartir → *Añadir a pantalla de inicio*.
- **PC (Chrome/Edge):** icono de instalar en la barra de direcciones.

Después de abrirla una vez con internet, también abre sin conexión.

## Hablar con Titi (voz)

- Toca el botón 🎙️ (abajo a la derecha) y habla, o escribe en su panel.
- Para que te escuche como Alexa, activa **Escuchar «Titi» siempre** (en su panel o en Ajustes) y di: *«Titi, agrega una tarea comprar pan mañana a las 5»*.
- Otros ejemplos: *«gasté 5 dólares en almuerzo»*, *«Juan me debe 20 dólares»*, *«agrega un examen de redes el viernes a las 10»*, *«marca el hábito tomar agua»*, *«¿qué tengo hoy?»*, *«deshacer lo último»*.
- **Límites reales:** solo escucha con la app abierta y la pantalla encendida (los navegadores no permiten escuchar en segundo plano); pide permiso al micrófono; el reconocimiento de voz lo hace el navegador y casi siempre necesita internet; funciona mejor en Chrome o Edge. En iPhone/Firefox puede fallar: escríbele en su panel. Con GitHub Pages (https) el permiso del micrófono se recuerda; abriendo el archivo directo, el navegador lo pregunta cada vez.

## Importante

- Recordatorios: avisan solo mientras la app está abierta. Para alarmas con la app cerrada, exporta el calendario (.ics) desde Ajustes y ábrelo en el calendario del celular.
- El PIN bloquea la pantalla de la app, pero no cifra los datos.
- **Tus datos se guardan en tu dispositivo** (no en la nube). Si cambias de celular o borras los datos del navegador se pierden:
  descarga un respaldo en **Ajustes → Descargar respaldo** y restáuralo en el otro dispositivo.
- El generador de preguntas del módulo de estudio funciona con reglas (sin IA). Para PDF, copia y pega el texto.
- También puedes usarla sin GitHub: abre `index.html` directamente en el navegador.
