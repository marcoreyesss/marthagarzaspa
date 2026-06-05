# Martha Garza Spa — Sitio web

Sitio web profesional para **Martha Garza Spa** (Cosmetóloga Certificada · Cumbres Madeira, Monterrey),
con sistema de reservación que envía las citas por **WhatsApp**.

---

## 📁 Qué incluye este paquete

```
index.html              ← El sitio web (archivo principal)
tweaks-panel.jsx        ← Componente del panel de ajustes
assets/
  ├─ mascarilla-facial.png   ← Foto del tratamiento facial (hero)
  └─ martha-cliente.png      ← Foto de Martha con clienta (sección "Sobre Martha")
```

> Mantén los archivos **tal cual están**, en estas mismas carpetas. Si mueves o
> renombras `assets/` o `tweaks-panel.jsx`, las fotos o el panel dejarán de cargar.

---

## 🚀 Cómo subirlo a GitHub y publicarlo gratis

### 1) Crear el repositorio
1. Entra a [github.com](https://github.com) e inicia sesión.
2. Haz clic en **New** (o el botón **+** arriba a la derecha → *New repository*).
3. Ponle un nombre, por ejemplo: `martha-garza-spa`.
4. Déjalo en **Public** y haz clic en **Create repository**.

### 2) Subir los archivos
1. En tu nuevo repositorio, haz clic en **Add file → Upload files**.
2. Arrastra **todos** los archivos de este paquete (incluida la carpeta `assets`).
3. Abajo haz clic en **Commit changes**.

### 3) Publicar con GitHub Pages (queda en internet)
1. En el repositorio ve a **Settings** (Ajustes).
2. En el menú lateral entra a **Pages**.
3. En *Branch* elige **main** y carpeta **/ (root)**, luego **Save**.
4. Espera 1–2 minutos y recarga: aparecerá la dirección pública de tu sitio,
   algo como `https://tu-usuario.github.io/martha-garza-spa/`.

¡Listo! Ya puedes compartir ese enlace en tu Instagram, WhatsApp, etc.

---

## 📱 El sistema de reservación

El formulario de citas **no necesita servidor**: cuando una clienta elige tratamiento,
día y hora, se abre WhatsApp con el mensaje ya escrito hacia el número
**811 661 0589**, listo para enviar.

**Para cambiar el número de WhatsApp:** abre `index.html`, busca la línea
`const WA="528116610589";` y reemplaza el número (formato: 52 + 10 dígitos).

---

## ✏️ Ajustes rápidos (sin tocar código)

Dentro de la herramienta de diseño, el botón **Tweaks** permite cambiar el color
de marca, la tipografía de los títulos y mostrar/ocultar la promoción
"Operación Vacaciones" cuando termine.

---

## 🔗 Contacto del negocio
- WhatsApp: 811 661 0589
- Instagram: [@marthagarzaspa](https://www.instagram.com/marthagarzaspa/)
- Ubicación: Cumbres Madeira, Monterrey, Nuevo León
