# 🎾 Pádel San Cristóbal

¡Bienvenido al proyecto **Pádel San Cristóbal**! Una plataforma web desarrollada para informar sobre la actualidad del pádel sancristobalense, la disponibilidad de turnos, eventos y torneos en la ciudad de San Cristóbal, Santa Fe.

---

## 🏫 Información Académica y Créditos

* **Institución:** Escuela Nacional Mariano Moreno N° 40
* **Carrera:** Tecnicatura Superior en Desarrollo de Software
* **Materia:** Tecnologías de la Información
* **Autor:** Martín Salas
* **Año:** 2026
* **Sitio de Referencia:** [San Cristóbal Pádel](https://sancristobalpadel.com/)

---

## 📋 Descripción del Proyecto

Este sitio web busca centralizar en un solo lugar la oferta deportiva de pádel en la localidad de San Cristóbal. Los usuarios pueden consultar las instalaciones de los distintos clubes, enterarse de las fechas de torneos, verificar disponibilidad para reserva de turnos, ubicar geográficamente cada complejo y ponerse en contacto de forma directa.

---

## 🚀 Funcionalidades Principales

* **Sección de Inicio / Hero:** Accesos rápidos a la reserva de turnos, calendario de torneos y rankings locales.
* **Catálogo de Complejos:** Información detallada sobre *Centro Pádel Racing*, *Match Point*, *Unidad Pádel* y *Zona Pádel*.
* **Organización en Cajas de Información:** Datos de instalaciones, horarios, tipos de superficie y servicios destacados organizados de manera clara.
* **Mapas Interactivos de Ubicación:** Integración con Google Maps para ubicar cada complejo (optimizado para ocultarse en pantallas móviles).
* **Contacto y Redes Sociales:** Enlaces a perfiles oficiales de Instagram y Facebook de los clubes.
* **Formulario de Contacto:** Consulta de turnos e inquietudes mediante formulario estructurado.
* **Navegación Móvil y Botón "Subir":** Experiencia fluida en cualquier dispositivo.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructuración semántica y accesible.
* **CSS3 Moderno:**
  * **Variables CSS (`:root`):** Paleta de colores unificada y fácil de mantener.
  * **CSS Grid & Flexbox:** Maquetación responsiva avanzada en 3 columnas.
  * **Media Queries:** Adaptación específica para Tablets (`760px`) y Celulares (`480px`).
* **Google Fonts:** Tipografía de títulos (`Bungee`) y cuerpo (`Lexend`).
* **Google Maps Embed API:** Geolocalización de canchas en la ciudad.

---

## 📁 Estructura del Proyecto

```text
├── Assets/
│   ├── Icons/          # Íconos SVG para la barra de navegación y favicon
│   ├── Match Point/    # Imágenes y logo de Match Point
│   ├── Racing/         # Imágenes y logo de Centro Pádel Racing
│   ├── Unidad/         # Imágenes y logo de Unidad Pádel
│   ├── ZonaPadel/      # Imágenes y logo de Zona Pádel
│   └── img/            # Encabezados e imágenes generales
├── css/
│   └── style.css       # Hoja de estilos principal con variables y media queries
├── index.html          # Estructura principal del sitio web
└── README.md           # Documentación del proyecto
```

---

## 📱 Adaptabilidad Responsiva

* **Escritorio (> 760px):** Layout en 3 columnas (Información en cajas | Mapa interactivo | Fotografía destacada).
* **Tablets (<= 760px):** Layout reorganizado a 2 columnas con mapas adaptados.
* **Celulares (<= 480px):** Layout vertical fluido a 1 sola columna. Los mapas `iframe` se ocultan automáticamente (`display: none`) para optimizar el rendimiento y consumo de datos móviles.

---

© 2026 **Martín Salas** — Tecnicatura en Desarrollo de Software (Escuela N° 40).