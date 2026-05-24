# Casa Mayis — Sitio Web Oficial

Sitio web estático para **Casa Mayis**, espacio de bienestar femenino ritualístico en San Francisco de Campeche, Campeche, México.

🌐 **Live:** [https://casamayis.com](https://casamayis.com)  
📸 **Instagram:** [@casamayis](https://instagram.com/casamayis)  
💬 **WhatsApp:** +52 938 134 1778

---

## Estructura del repositorio

```
casamayis/
├── index.html              # Página principal (única página)
├── 404.html                # Página de error personalizada
├── sitemap.xml             # Para indexación en buscadores
├── robots.txt              # Instrucciones para crawlers y LLMs
├── llms.txt                # Información estructurada para IAs
├── assets/
│   ├── images/
│   │   └── og-image.jpg    # Imagen para redes sociales (1200×630)
│   └── icons/
│       └── favicon.png     # Ícono del sitio
└── README.md
```

---

## Tecnologías

- HTML5 semántico — sin frameworks, sin dependencias
- CSS con custom properties (`--crema`, `--dorado`, `--tierra`, etc.)
- Google Fonts: Cormorant Garamond + Jost
- Schema.org LocalBusiness para SEO local
- Open Graph para WhatsApp / redes sociales

---

## Despliegue en GitHub Pages

1. Ve a **Settings → Pages**
2. En *Source*, selecciona **Deploy from a branch**
3. Elige la rama `main` y la carpeta `/ (root)`
4. Guarda — el sitio estará en `https://<usuario>.github.io/<repo>` en unos minutos

### Dominio personalizado (casamayis.com)

Agrega un archivo `CNAME` en la raíz del repo con el contenido:
```
casamayis.com
```
Luego configura los registros DNS con tu proveedor de dominio apuntando a GitHub Pages.

---

## Actualizar contenido

Todo el contenido está en `index.html`. Para actualizar:

- **Precios** — busca el precio en el archivo y cámbialo directamente
- **WhatsApp** — el número `529381341778` aparece en los links `wa.me/`. Reemplaza todos si cambia
- **Horarios** — busca "Lunes a Sábado" en el HTML y en `llms.txt`
- **Nuevos servicios** — duplica un bloque `.servicio-card` o `.masaje-item` existente

---

© 2026 Casa Mayis · Campeche, México
