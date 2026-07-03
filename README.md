# Certificación Laboral — Alliance Network E.I.R.L.

Certificado laboral con diseño corporativo (formato A4, una página), listo para desplegar en Vercel.

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Página principal (la que sirve Vercel en la raíz del dominio). Certificado **editable**: haz clic sobre cualquier texto para modificarlo y pulsa **«Descargar PDF»**. Se adapta automáticamente a pantallas de celular. |
| `certificado-laboral.html` | Copia idéntica de `index.html`, por si prefieres abrirla en local. |
| `certificado-laboral.pdf` | Versión **final lista**, con el bloque de firma incluido. |

## Despliegue en Vercel

El proyecto es un sitio estático puro: no necesita build ni configuración.
Al importar el repositorio en Vercel, deja *Framework Preset* en **Other** y no definas comando de build.
`index.html` se sirve automáticamente en la raíz del dominio.

## Cómo editar

1. Abre la página desplegada (o `index.html` en cualquier navegador).
2. Haz clic sobre el texto que quieras cambiar (nombre, fecha, salario, funciones, etc.) y escribe directamente.
3. Pulsa el botón **Descargar PDF** de la barra superior y elige «Guardar como PDF» con márgenes en «Ninguno».

La barra de ayuda superior y el panel de personalización no aparecen en el PDF impreso.

## Personalizar firma y logo

Justo debajo de la barra superior hay un panel con dos grupos de opciones:

- **Firma**: elige entre tres estilos prediseñados (**Clásica**, **Ejecutiva**, **Ricardo**), pulsa **«Dibujar la mía»** para firmar a mano con el mouse o el dedo dentro de un recuadro, o **«Subir imagen»** para usar una foto/escaneo de una firma real (ideal en PNG con fondo transparente).
- **Logo**: pulsa **«Subir logo»** para reemplazar el monograma «AN» por el logotipo de la empresa (se ajusta automáticamente al recuadro), o **«Usar iniciales»** para volver al monograma por defecto.

Estas elecciones se guardan en el navegador (localStorage) para que no se pierdan al recargar la página.
