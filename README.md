<p align="center">
  <img src="https://avatars.githubusercontent.com/u/72231436?v=4" alt="Avatar" width="120" style="border-radius: 50%;" />
</p>

# Landing Page IA - Panadería Montoya

> **“Una experiencia multimedia que despierta tus sentidos.”**

---

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-5.3.0-purple?logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Fonts-Montserrat%20%7C%20Playfair_Display-lightgrey?logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/AOS-2.3.4-brightgreen?logo=none&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Pages-deployed-green?logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 🧠 Descripción general

Esta landing page estática, creada con IA y tecnologías web modernas, actúa como **galería interactiva** para tu campaña publicitaria de **Panadería Montoya**. Incluye:

* **Spot IA** incrustado desde Google Drive.
* **Carrusel** horizontal de hasta 7 imágenes generadas por IA, con avance automático y efecto zoom al pasar el mouse.
* **Audio**: voz TTS y composición musical IA integrados.
* **Guion** narrativo presentado en una tarjeta.
* **Descargas** de recursos multimedia.
* Diseño **responsive**, paleta de colores basada en tonos de pan, tipografías elegantes y animaciones de scroll.

Desarrollado como proyecto final del **Diplomado en Inteligencia Artificial**, su objetivo es mostrar y expandir contenido digital con herramientas versátiles.

---

## 📋 Estructura del proyecto

```
panaderia-landing/
├── index.html
├── assets/
│   ├── hero-bg.jpg
│   ├── ia-pan-1.jpg
│   ├── ia-pan-2.jpg
│   ├── ia-pan-3.jpg
│   ├── ia-pan-4.jpg
│   ├── ia-pan-5.jpg
│   ├── ia-pan-6.jpg
│   ├── ia-pan-7.jpg
│   ├── tts-voz.mp3
│   ├── musica-ia.mp3
│   └── favicon.ico
```

---

## 🚶‍♂️ Proceso de desarrollo

1. **Planeación**

   * Definición de secciones: video, galería, audio, guion y descargas.
   * Selección de stack ligero: HTML5, CSS3, Bootstrap y AOS.

2. **Maquetación**

   * Estructura semántica en `index.html`.
   * Integración de Google Fonts para Montserrat (cuerpo) y Playfair Display (títulos).

3. **Estilizado**

   * Paleta de colores en CSS basada en tonos de pan.
   * Esquinas redondeadas y sombras suaves.

4. **Interactividad**

   * Carousel automático de Bootstrap (intervalo 3 s).
   * Animaciones de scroll con AOS (fade-up, fade-in).
   * Zoom-on-hover en imágenes.

5. **Integración de recursos IA**

   * Embebido de video desde Google Drive (`/preview`).
   * Imágenes generadas por prompts IA.
   * Audio TTS y música IA con controles `<audio>`.

6. **Despliegue**

   * Subida al repositorio público en GitHub.
   * Habilitación de GitHub Pages en Settings > Pages.

---

## 💾 Instalación y despliegue

1. **Clonar repositorio**

   ```bash
   git clone https://github.com/sjaquer/panaderia-landing.git
   cd panaderia-landing
   ```

2. **Ver localmente**

   * Abre `index.html` en tu navegador o usa Live Server de VS Code.

3. **Despliegue en GitHub Pages**

   * Sube todos los archivos al branch `main`.
   * En Settings > Pages, establece `main` como fuente.
   * Tu sitio quedará disponible en `https://tuUsuario.github.io/panaderia-landing/`.

---

## ✅ Uso

* Usa el menú superior para navegar a cada sección.
* El **Spot IA** requiere clic para reproducir.
* El **carrusel** avanza solo; pasa el mouse para hacer zoom.
* Usa los botones de descarga para obtener el audio TTS y la música IA.

---

## 📌 Consideraciones técnicas

* **Sitio estático** sin backend.
* **Responsive**: adaptado a móviles y desktop gracias a Bootstrap.
* **Tipografías**: Montserrat (cuerpo) y Playfair Display (títulos).
* **Animaciones**: scroll (AOS) y hover (CSS transitions).

---

## 📝 Licencia

Licencia **MIT**. Puedes usar, modificar y distribuir este proyecto libremente.

---

## 👨‍💻 Autor

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/72231436?v=4" alt="Avatar" width="100" style="border-radius: 50%;" />
</p>

**sjaquer@**
Proyecto final Diplomado en Inteligencia Artificial
Repositorio original: [github.com/sjaquer/panaderia-landing](https://github.com/sjaquer/panaderia-landing)
