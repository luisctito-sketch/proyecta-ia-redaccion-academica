# PROYECTA-IA · Viñetas, Conectores y Párrafos

Chatbot/herramienta transversal para el Proyecto de Grado.

## Repositorio recomendado
`proyecta-ia-redaccion-academica`

## URL esperada en GitHub Pages
`https://luisctito-sketch.github.io/proyecta-ia-redaccion-academica/`

## Funciones
- Reglas para viñetas y listas verticales.
- Tabla pedagógica de conectores por relación lógica.
- Guía para construcción de párrafos académicos.
- Ejemplos aplicados a Telecomunicaciones, Sistemas de Control y Automatización, y Electromedicina.
- Modelos de cinco párrafos (introducción + desarrollo + cierre) para las tres menciones.
- Revisor local de texto pegado.
- Carga local de TXT, DOCX y PDF.
- Detección de inconsistencias frecuentes de viñetas, repetición de conectores, primera persona y párrafos poco desarrollados o excesivamente extensos.
- Prompt para revisión semántica profunda en ChatGPT.
- Acceso mediante `https://luisctito-sketch.github.io/proyecta-ia-acceso/access.js`.

## Archivos
- `index.html`
- `styles.css`
- `app.js`
- `FUENTES_Y_CRITERIOS.md`

## Dependencias de navegador
Para la extracción local de archivos se cargan desde CDN:
- Mammoth.js para `.docx`.
- PDF.js para `.pdf`.

Los documentos seleccionados por el estudiante se procesan en el navegador por este módulo; el código no implementa una carga del archivo a un servidor propio.

## Publicación
1. Crear repositorio público `proyecta-ia-redaccion-academica`.
2. Subir los cuatro archivos en la raíz.
3. Activar GitHub Pages desde `main` / root.
4. Añadir el enlace al portal principal PROYECTA-IA.
