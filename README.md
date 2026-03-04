# proyecto-smart.budget
Landing page, implementando interfaz web responsiva aplicando método SASS

SmartBudget – Landing Page

1. Descripción del Proyecto
SmartBudget es una solución conceptual de landing page para una plataforma de gestión financiera personal. Este proyecto fue desarrollado para demostrar el dominio de maquetación avanzada, combinando la potencia de Bootstrap 4 con la flexibilidad y orden de SASS.

El objetivo principal es ofrecer una experiencia de usuario (UX) fluida, con un diseño limpio (limpio y corporativo) y una arquitectura de código escalable.

2. Tecnologías Utilizadas
HTML5: Estructura semántica.

CSS3 & SASS: Arquitectura avanzada de estilos.

Bootstrap 4.6: Sistema de grillas (Grid) y componentes responsivos.

Metodología BEM: Nomenclatura lógica para clases CSS (bloque__elemento--modificador).

Google Fonts: Integración de la fuente Inter para legibilidad moderna.

JavaScript: Interactividad de componentes (Navbar y Tabs de Login).

3. Estructura de Sass (Arquitectura 7-1)
El proyecto utiliza una versión optimizada de la metodología 7-1 para asegurar que el mantenimiento sea sencillo:

Plaintext
scss/
│
├── abstracts/     # _variables.scss (Colores, fuentes, tokens)
├── base/          # _reset.scss (Estilos globales y animaciones)
├── components/    # _buttons.scss, _cards.scss, _navbar.scss
├── layout/        # _hero.scss, _footer.scss
└── main.scss      # Archivo maestro de importación
Nota: El archivo main.scss es el único que se compila, generando el archivo css/main.css que consume el HTML.

4. Metodología BEM
Se implementó BEM (Block Element Modifier) para evitar la especificidad excesiva y colisiones de estilos:

Bloque: .auth-pro, .feature-card, .navbar-custom

Elemento: .auth-pro__tabs, .nav-link-custom, .brand-logo

Modificador: .nav-link.active, .btn-primary:hover

5. Características Principales
Navegación Inteligente: Navbar fija (fixed-top) con cambio de estilo en dispositivos móviles.

Sección Hero: Diseño de alto impacto con llamadas a la acción (CTA) claras.

Auth System (UI): Formulario de autenticación profesional con pestañas (Tabs) funcionales para intercambiar entre Login y Registro.

Cards Dinámicas: Efectos de elevación (hover) y sombras suaves para mejorar la profundidad visual.

Totalmente Responsivo: Adaptado para Smartphones, Tablets y Desktop usando puntos de interrupción (breakpoints) de Bootstrap.

- Javiera Ramirez - bootcamp desarrollador Front end
