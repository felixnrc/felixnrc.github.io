# 💻 cv.felixnrc.ar — CV y Portfolio Técnico

Portfolio personal y CV interactivo de Felix Natanael Rojas Carballo, SysAdmin Sr. con más de 5 años de experiencia en infraestructura crítica 24/7.

🔗 **[cv.felixnrc.ar](https://cv.felixnrc.ar)**

---

## 🧩 ¿Qué es este proyecto?

Sitio web estático que funciona como CV digital técnico, orientado a reclutadores y equipos de RRHH. Incluye:

- 👤 **Hero** — presentación con foto, rol y efecto de escritura animado (typewriter)
- 🖥️ **Sobre mí** — terminal visual con stack core y tarjetas de estadísticas
- 📋 **Experiencia** — timeline vertical con 5 posiciones (Venezuela → Argentina, 2016–presente)
- 🧠 **Skills** — grilla de tecnologías organizadas por categoría
- 🏅 **Certificaciones** — Cisco CyberOps, Platzi y más
- 🔧 **Proyectos open source** — con links a GitHub
- 📬 **Contacto** — links a GitHub, LinkedIn y email

---

## ⚙️ Tecnologías

| Tecnología | Uso |
|---|---|
| **HTML5** | Estructura del documento |
| **CSS3** | Estilos con variables CSS, animaciones y diseño responsive |
| **JavaScript vanilla** | Typewriter, scroll reveal con `IntersectionObserver`, menú mobile, animación de foto |
| **Google Fonts** | Tipografías Inter y JetBrains Mono |
| **GitHub Pages** | Hosting estático con dominio personalizado |

> Sin frameworks, sin dependencias, sin build step. Archivo único `index.html`.

---

## 🚀 ¿Cómo funciona?

El sitio es un archivo HTML monolítico con estilos incrustados y JavaScript al pie. No requiere compilación ni servidor.

```
felixnrc.github.io/
├── index.html     # Todo el sitio (HTML + CSS + JS)
├── profile.jpg    # Foto de perfil
├── CNAME          # Dominio personalizado: cv.felixnrc.ar
└── README.md
```

### Características técnicas

- 🎨 **Tema oscuro** con paleta verde neón (`#00ff00`) y cian (`#00ffff`)
- 📱 **Responsive** con breakpoints para mobile (menú hamburguesa, grid de 1 columna)
- ✨ **Animaciones**: reveal al hacer scroll, glow en la foto, pulso en el dot del trabajo actual
- 🔤 **Typewriter**: rota entre roles profesionales con efecto de escritura/borrado

### Despliegue

El sitio se publica automáticamente en GitHub Pages al hacer push a `main`. El archivo `CNAME` apunta el dominio `cv.felixnrc.ar` al hosting de GitHub.

---

## 🌐 Ver en vivo

```
https://cv.felixnrc.ar
```

---

## 📬 Contacto

**felixnrc@protonmail.com** · [GitHub](https://github.com/felixnrc) · [LinkedIn](https://linkedin.com/in/felixnrc) · Neuquén, Patagonia 🇦🇷
