# App Panatta

Guía interactiva de tu semana de fuerza (Días A–F, 30 ejercicios) con mapa
muscular tipo Garmin (frente/espalda, primarios/secundarios) y el detalle de
series, repeticiones, descanso y cómo hacer cada ejercicio.

Es un solo archivo (`index.html`), no necesita servidor ni build.

## Publicarla en GitHub Pages

1. Creá un repositorio nuevo en GitHub (público o privado, cualquiera sirve
   para Pages si tu cuenta lo permite).
2. Subí este archivo `index.html` (y este `README.md` si querés) a la raíz
   del repositorio.
3. Andá a **Settings → Pages**.
4. En "Build and deployment" elegí **Deploy from a branch**, rama `main`
   (o `master`) y carpeta `/ (root)`.
5. Guardá y esperá uno o dos minutos.
6. Tu app va a quedar disponible en:
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Verla sin GitHub

También podés simplemente abrir `index.html` con doble clic en tu
computadora — funciona igual, ya que no depende de ningún servidor.

## Editar los ejercicios

Todo el contenido (nombres, series, repeticiones, descansos, músculos y
explicaciones) está en el array `DAYS` cerca del final del archivo, dentro
de la etiqueta `<script>`. Podés editarlo directo en cualquier editor de
texto.
