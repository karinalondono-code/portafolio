# Karina Londoño — sitio web de marca personal

Sitio estático listo para publicar, sin compilación ni dependencias de JavaScript.

## Archivos
- `index.html`: estructura, metadatos, secciones y enlaces.
- `styles.css`: diseño adaptable, tipografía y animaciones.
- `script.js`: menú móvil, efectos de aparición y trayectoria profesional (editable en el arreglo `experiences`).
- `assets/karina-estudio.jpg`: fotografía principal suministrada por la usuaria.

## Vista local
Abre `index.html` en el navegador o ejecuta `python3 -m http.server 8000` desde esta carpeta y visita `http://localhost:8000`.

## Publicación
Sube el contenido de esta carpeta a Netlify, Vercel, GitHub Pages o un servidor estático. Mantén la estructura de carpetas. Configura tu dominio y HTTPS en el proveedor.

## Personalización
- Cambia colores en `:root` de `styles.css`.
- Actualiza experiencia en `script.js`.
- Edita textos, enlaces y correo en `index.html`.
- Comprueba que la URL del portafolio de Canva siga vigente; se transcribió de la hoja de vida.
- Los años 'Actualidad' provienen de la hoja de vida de octubre de 2026 y deben actualizarse si cambian.
- El sitio utiliza Google Fonts por CDN: si necesitas operación sin terceros, aloja fuentes autorizadas localmente y modifica el CSS.

## Privacidad
Se excluyeron intencionalmente el número de identificación y los teléfonos de referencias personales. El número profesional de contacto y el correo sí se incluyeron como figuran en la hoja de vida.

## Pendiente antes de publicar
Verificar datos, enlaces, consentimiento para mostrar foto y teléfono; añadir dominio propio si se dispone. Los botones de contacto abren el correo, WhatsApp y teléfono; no hay formulario ni backend.
