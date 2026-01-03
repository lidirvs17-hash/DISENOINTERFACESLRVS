# 🛒 The Fiction Pantry - Supermercado Premium de Cultura Pop

[![Licencia: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Grado: DAW](https://img.shields.io/badge/Grado-DAW-blue.svg)](#)
[![Estado: Completado](https://img.shields.io/badge/Estado-Completado-green.svg)](#)

**The Fiction Pantry** es un proyecto de desarrollo de interfaces web que recrea un e-commerce moderno especializado en productos icónicos de videojuegos, cine y literatura fantástica. El sitio combina una estética minimalista "Clean Design" con elementos narrativos inmersivos.

## 🚀 Características del Proyecto

* **Diseño Responsive:** Interfaz totalmente adaptativa (Desktop, Tablet y Mobile) utilizando CSS Grid y Flexbox.
* **Arquitectura de Pantalla Partida (Split-Screen):** Diseño de vanguardia en las páginas de detalle para maximizar el impacto visual del producto.
* **Identidad Visual Consistente:** Paleta de colores funcional basada en psicología del color y tipografía optimizada para lectura digital.
* **Uniformidad de Interfaz:** Uso de "Caja Maestra" para tarjetas de producto y componentes reutilizables.

## 🎨 Guía de Estilo (Comunicación Visual)

El proyecto se basa en una paleta cromática estratégica para guiar la experiencia del usuario (UX):

| Elemento | Color Hex | Propósito Psicológico |
| :--- | :--- | :--- |
| **Corporativo** | `#0056b3` (Azul) | Transmite confianza, seguridad y profesionalidad. |
| **Acción (CTA)** | `#ff8c00` (Naranja) | Genera energía e incentiva la conversión (compra). |
| **Categorías** | `#2d5a27` (Verde) | Evoca frescura, naturaleza y calidad orgánica. |
| **Premium** | `#b8860b` (Dorado) | Reservado para ediciones limitadas y productos especiales. |

## 🛠️ Tecnologías Utilizadas

* **HTML5 Semántico:** Estructura optimizada para accesibilidad y SEO (`<article>`, `<section>`, `<header>`, `<nav>`).
* **CSS3 Avanzado:** * Uso de **Variables CSS** para una gestión eficiente de la paleta de colores.
    * **Media Queries** para el flujo responsivo del contenido.
    * **Filtros y Efectos:** Implementación de resplandores atmosféricos (`nuka-glow`) y sombras dinámicas.
* **MockFlow:** Prototipado previo de alta fidelidad para Desktop y Mobile.

## 📂 Estructura del Repositorio

```text
/
├── index.html              # Página principal (Catálogo)
├── detalle-nuka.html       # Páginas de detalle de producto
├── detalle-lembas.html     # ...
├── detalle-spidey.html     # ...
├── css/
│   └── styles.css          # Hoja de estilos global y responsive
└── img/
    ├── logo.png            # Logotipo corporativo circular
    └── [imágenes-productos]# Recursos optimizados (700KB - 2MB)
