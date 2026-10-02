# Thenosis · Coming soon

Página "en construcción" de www.thenosis.com (destino del QR de las tarjetas).
HTML estático, sin build: lo que está en esta carpeta es exactamente lo que se publica.

- **Producción (www.thenosis.com):** hosting del cliente en Duplika, misma cuenta que adequate.lat. Se sube a mano: `index.html`, `og.jpg`, `favicon-32.png`, `apple-touch-icon.png` y la carpeta `assets/` a la carpeta del dominio en el cPanel. No subir `README.md` ni `.git`.
- **DNS:** en Namecheap (BasicDNS, sin delegar a Duplika): registros `A` de `@` y `www` → `50.28.85.119`.
- **Vercel (thenosis.vercel.app):** copia de prueba; el push a `main` la deploya sola. No es el dominio.

Idioma: se elige solo por el idioma del navegador (español → ES, el resto → EN), se recuerda la elección del selector, y se puede forzar con `?lang=es` / `?lang=en`.
Colores y tipografía según el Manual de Marca 2026 (Montserrat; Océano #14404f, Oliva #6e7c4c, Tierra #c5a06e, Marfil #f3f2ec).
