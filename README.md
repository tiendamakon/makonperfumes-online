# MAKON Perfumes & Cosmética — Landing (v2)
Sitio para **makonperfumes.online** con Vite + React + Tailwind + formularios con FormSubmit.

## Variables que debes cambiar
- En `src/App.jsx` edita `WHATSAPP` con tu número real (formato `+34...`).

## Deploy rápido en Vercel
1. Sube esta carpeta al repo de GitHub (no subas el ZIP directamente).
2. Vercel → New Project → conecta el repo.
3. Build: `npm run build` • Output: `dist`.
4. Añade dominio `makonperfumes.online` y pon estos DNS en tu registrador:
   - Apex A → `76.76.21.21`
   - www CNAME → `cname.vercel-dns.com`

## Formularios (sin backend)
Usamos **FormSubmit** apuntando a `hola@makonperfumes.online`:
- Newsletter, B2B y Contacto envían email a tu buzón y redirigen a `/thanks.html`.
- Si cambias el email, actualiza `FORM_ENDPOINT` en `src/App.jsx`.

## Páginas legales
- `/privacy.html` y `/terms.html` editables con tus datos.
