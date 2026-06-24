# Queenland Tech - Sitio Web Oficial

[![Queenland Tech](https://img.shields.io/badge/Queenland%20Tech-Fibra%20%C3%93ptica-%23A6CE39)](https://www.queenlandtech.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 Descripción

Sitio web oficial de **Queenland Tech**, empresa especializada en **formación técnica en fibra óptica**, certificaciones y capacitación para profesionales y empresas de telecomunicaciones en República Dominicana.

**No vendemos internet residencial. Formamos a quienes lo construyen y mantienen.**

---

## 🎯 Nuestros Servicios / Cursos

| # | Curso / Servicio | Descripción |
|---|------------------|-------------|
| 1 | **Curso de Fibra Óptica FTTH** | Formación completa en despliegue, fusión y certificación de redes FTTH |
| 2 | **Certificación en Redes** | Preparación para certificaciones nacionales e internacionales |
| 3 | **Formación para Empresas** | Programas a medida para equipos técnicos corporativos |
| 4 | **Entrenamiento Práctico** | Capacitación hands-on con equipo real (fusores, OTDR) |
| 5 | **Capacitación In-Company** | Formación en tus instalaciones sin interrupciones |
| 6 | **Outsourcing de Técnicos** | Provisión de técnicos certificados para proyectos |

---

## 📁 Estructura del Proyecto
queenland-tech/
│
├── index.html # Página principal (Home)
├── index-3.html # Home alternativo
├── about.html # Sobre Nosotros
├── contact.html # Contacto
├── services.html # Todos los Cursos
├── services-carousel.html # Cursos en carrusel
├── service-d-broadband.html # Curso Fibra Óptica FTTH
├── service-d-iptv.html # Certificación en Redes
├── service-d-cyber-security.html # Formación para Empresas
├── service-d-landline.html # Entrenamiento Práctico
├── service-d-tv.html # Capacitación In-Company
├── service-d-connectivity.html # Outsourcing de Técnicos
├── team.html # Nuestro Equipo (grid)
├── team-carousel.html # Equipo en carrusel
├── team-details.html # Detalle del equipo
├── gallery.html # Galería Masonry
├── gallery-carousel.html # Galería en carrusel
├── blog-grid.html # Blog y Recursos Técnicos
├── blog-carousel.html # Blog en carrusel
├── blog-details.html # Detalle de artículo
├── packages.html # Programas de Certificación
├── packages-carousel.html # Certificaciones en carrusel
├── products.html # Materiales y Equipos
├── reviews.html # Testimonios
├── reviews-carousel.html # Testimonios en carrusel
├── faq.html # Preguntas Frecuentes
├── 404.html # Página de error 404
├── cart.html # Carrito de compras
├── checkout.html # Finalizar compra
├── login.html # Inicio de sesión
│
├── assets/ # Recursos del sitio
│ ├── css/ # Estilos CSS
│ ├── js/ # JavaScripts
│ ├── images/ # Imágenes y gráficos
│ │ ├── gallery/ # Imágenes de galería
│ │ ├── blog/ # Imágenes del blog
│ │ ├── team/ # Fotos del equipo
│ │ └── resources/ # Recursos gráficos
│ ├── fonts/ # Fuentes tipográficas
│ └── vendors/ # Librerías externas
│
├── inc/ # Scripts PHP
│ └── sendemail.php # Envío de formularios de contacto
│
└── README.md # Este archivo

text

---

## 🎨 Identidad Visual

### Paleta de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| Verde Lima | `#A6CE39` | Botones, acentos, enlaces, elementos destacados |
| Negro | `#000000` | Headers, textos principales |
| Blanco | `#FFFFFF` | Fondos limpios |
| Gris Neutro | `#808080` | Textos secundarios |

### Tipografía

- **Fuente principal:** Outfit / Montserrat / Roboto / Helvetica Neue
- **Estilo:** Sans-serif moderna, legible y tecnológica

---

## 📞 Información de Contacto

| Tipo | Detalle |
|------|---------|
| **Dirección** | Higüey, República Dominicana |
| **Teléfono Negocio** | 849-496-7296 |
| **Oficina** | 809-951-2786 |
| **Correo General** | info@queenlandtech.com |
| **Correo Gerente** | rbatista@queenlandtech.com |
| **Correo Operaciones** | ltorres@queenlandtech.com |
| **Sitio Web** | www.queenlandtech.com |

### Redes Sociales

- 📘 Facebook: [@QueenlandTech](https://facebook.com)
- 📸 Instagram: [@QueenlandTech](https://instagram.com)
- 🐦 Twitter: [@QueenlandTech](https://twitter.com)
- ▶️ YouTube: [Queenland Tech](https://youtube.com)

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
|------------|-------------|
| **HTML5** | Estructura del sitio |
| **CSS3** | Estilos y animaciones |
| **JavaScript** | Interactividad y funcionalidades |
| **jQuery** | Manipulación del DOM |
| **Bootstrap** | Framework CSS responsive |
| **Owl Carousel** | Carruseles y sliders |
| **GSAP** | Animaciones avanzadas |
| **PHP** | Procesamiento de formularios (contacto) |

---

## 📧 Configuración del Formulario de Contacto

Para que el formulario de contacto funcione correctamente, edita el archivo `inc/sendemail.php`:

```php
// Configuración de correo
define( "RECIPIENT_NAME", "Queenland Tech" );
define( "RECIPIENT_EMAIL", "info@queenlandtech.com" );

// Opcional: copia a otros correos
// define( "CC_EMAIL", "ltorres@queenlandtech.com" );
// define( "BCC_EMAIL", "rbatista@queenlandtech.com" );
Requisitos del servidor:

PHP 7.0 o superior

Función mail() habilitada

Servidor con soporte SMTP (recomendado)

🚀 Instalación y Uso
Clonar el repositorio

bash
git clone https://github.com/queenlandtech/queenland-web.git
Subir archivos al servidor

Copia todos los archivos a la carpeta raíz de tu hosting

Asegúrate de mantener la estructura de carpetas

Configurar permisos

La carpeta assets/images/ debe tener permisos de escritura (755)

El archivo inc/sendemail.php debe ser ejecutable (644)

Verificar el formulario de contacto

Realiza una prueba de envío

Confirma que los correos llegan a info@queenlandtech.com

📱 Responsive Design
El sitio está diseñado para ser completamente responsive y funcionar correctamente en:

💻 Desktop (1920x1080 y superiores)

📟 Laptop (1366x768)

📱 Tablet (768x1024)

📲 Móvil (375x667 y superiores)

🔧 Personalización
Cambiar imágenes
Las imágenes de la galería y el blog se encuentran en:

assets/images/gallery/

assets/images/blog/

assets/images/team/

Cambiar colores
Los colores corporativos están definidos en el <style> de cada página:

css
/* Color principal - Verde Lima */
.ienet-btn {
    background-color: #A6CE39 !important;
}
Cambiar textos
Todos los textos están directamente en los archivos HTML. Puedes editarlos con cualquier editor de texto.

📄 Licencia
Este proyecto es propiedad de Queenland Tech. Todos los derechos reservados.

© Copyright 2025 por Queenland Tech.

👥 Equipo
Rol	Nombre	Contacto
Gerente Administrativa	Reyna Batista de los Santos	rbatista@queenlandtech.com
Director de Operaciones / Instructor Master	Luis R. Torres	ltorres@queenlandtech.com
📌 Notas Importantes
⚠️ Queenland Tech no vende internet residencial

🎓 Somos especialistas en formación técnica en fibra óptica

🔧 Ofrecemos outsourcing de técnicos certificados

🏢 Capacitamos empresas de telecomunicaciones

🆘 Soporte
Para cualquier consulta sobre el sitio web:

📧 Email: info@queenlandtech.com

📞 WhatsApp: 849-496-7296

🏢 Oficina: 809-951-2786

🙏 Agradecimientos
Ienet Template - Base del diseño visual

Bootstrap - Framework CSS

Owl Carousel - Sliders y carruseles

GSAP - Animaciones

*Documentación actualizada - Junio 2025*

text

---

## 📋 Resumen del README.md

| Sección | Contenido |
|---------|-----------|
| **Descripción** | Presentación de Queenland Tech como empresa de formación |
| **Servicios** | Lista de 6 cursos/servicios principales |
| **Estructura** | Árbol de archivos completo del proyecto |
| **Identidad Visual** | Paleta de colores (#A6CE39, negro, blanco, gris) y tipografía |
| **Contacto** | Dirección, teléfonos, correos y redes sociales |
| **Tecnologías** | HTML5, CSS3, JS, jQuery, Bootstrap, Owl Carousel, GSAP, PHP |
| **Configuración PHP** | Instrucciones para el formulario de contacto |
| **Instalación** | Pasos para clonar y subir al servidor |
| **Personalización** | Cómo cambiar imágenes, colores y textos |
| **Equipo** | Reyna Batista y Luis R. Torres |
| **Soporte** | Datos de contacto para consultas |


#   Q u e e n l a n d -  
 #   Q u e e n l a n d -  
 