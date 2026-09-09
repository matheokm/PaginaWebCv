# Portafolio Web Profesional - Kevin Matheo Paspuel Enríquez

Sitio web y portafolio interactivo de alto rendimiento diseñado para fortalecer la presencia profesional y marca personal de **Kevin Matheo Paspuel Enríquez** (*Ingeniero en Sistemas | UISRAEL*).

---

## 🌟 Características Principales

- **Arquitectura Limpia & Cero Dependencias**: Desarrollado con HTML5 semántico, CSS3 moderno (con variables y efectos de *glassmorphism*) y JavaScript vanilla modular.
- **Sistema de Temas Dinámico**: Modo Oscuro (Dark Tech) y Modo Claro (Minimalista) con detección automática del sistema y persistencia mediante `localStorage`.
- **Efecto Typewriter**: Animación fluida de roles en la portada (`Ingeniero en Sistemas`, `Software Developer`, `Cybersecurity Enthusiast`, etc.).
- **Filtros Interactivos de Portafolio**: Filtrado en tiempo real de proyectos e investigaciones (Investigación Científica, Desarrollo de Software, Ciberseguridad).
- **Copiado Rápido al Portapapeles**: Botón de un solo clic para copiar la dirección de correo con notificación *toast* flotante.
- **Formulario de Contacto Funcional**: Validación integrada y generación automática de mensaje para envío directo.
- **100% Responsivo (Mobile First)**: Adaptado para teléfonos móviles, tabletas, portátiles y pantallas 4K.
- **SEO & Open Graph Optimizado**: Metadatos listos para previsualizaciones enriquecidas al compartir tu enlace en LinkedIn, WhatsApp y Twitter.

---

## 📁 Estructura del Proyecto

```text
PaginaWebCv/
│
├── index.html            # Estructura principal, secciones y contenido
├── css/
│   └── styles.css        # Estilos visuales, variables de tema y animaciones
├── js/
│   └── main.js           # Lógica interactiva (tema, filtros, copiado, menú móvil)
└── README.md             # Documentación y guía de despliegue
```

---

## 🚀 Cómo Visualizar en Tu Equipo Local

Puedes abrir el sitio de cualquiera de las siguientes formas:

1. **Directamente en tu navegador**:
   Haz doble clic sobre el archivo `index.html` en la carpeta `d:\Nueva carpeta\PaginaWebCv`.

2. **Con un servidor local rápido (Node.js)**:
   Abre una terminal en esta carpeta y ejecuta:
   ```bash
   npx serve .
   ```
   o
   ```bash
   python -m http.server 8000
   ```
   Luego ingresa a `http://localhost:8000` en tu navegador.

---

## 🌐 Cómo Desplegar Gratis en Internet

### Opción A: GitHub Pages (Recomendado para mostrar con tu GitHub)
1. Crea un repositorio en tu cuenta de GitHub (por ejemplo, `kevin-paspuel-portfolio` o `matheokm.github.io`).
2. Sube estos archivos al repositorio con Git:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Portafolio Kevin Paspuel"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
   git push -u origin main
   ```
3. En GitHub, ve a **Settings > Pages** y activa la rama `main` en la raíz `/`.
4. ¡Tu web estará en vivo en pocos segundos con dirección pública gratuita y certificado SSL (HTTPS)!

### Opción B: Vercel o Netlify
- Solo arrastra y suelta la carpeta `PaginaWebCv` en [app.netlify.com/drop](https://app.netlify.com/drop) o impórtala desde tu repositorio de GitHub en [vercel.com](https://vercel.com).

---

## ✏️ Personalización Rápida

- **Actualizar tu Correo Real**: Abre `index.html` y reemplaza `kevin.paspuel@ejemplo.com` por tu correo electrónico real (aparece en el Hero, en la sección de contacto y en el footer).
- **Añadir tu CV en PDF**: Si tienes tu currículum en PDF, colócalo dentro de la carpeta (por ejemplo `assets/CV_Kevin_Paspuel.pdf`) y actualiza el botón de descarga.
- **Agregar nuevos proyectos**: En la sección `#projects` de `index.html`, copia un bloque de `<div class="project-card">` y personaliza los textos, enlaces y etiquetas.
