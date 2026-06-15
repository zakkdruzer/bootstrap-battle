# Bootstrap Landing Missions - PixelForge & La Cantina del Dev

Autor: **José Ignacio Gajardo Soto / Zakkdruzer**

## Misión 1 – 🎮 PixelForge Games

Landing page para un estudio de videojuegos ficticio, construida con Bootstrap 5.  
Incluye navegación responsive, anuncio de lanzamiento, galería de screenshots y funcionalidades de interacción para fans.

**Componentes y utilidades usadas:**

- Navbar (brand, colapso, dropdown, hamburguesa)
- Alert descartable (anuncio de lanzamiento)
- Carousel con indicadores, controles y captions
- Cards en grilla responsive (`row` + `col-*`, `h-100`, `d-flex`)
- Tablas (`table-striped`, `table-hover`, `table-bordered`, `table-responsive`)
- Formulario con validación visual (`novalidate`, `was-validated`, `invalid-feedback`)
- Modal para ver el tráiler oficial
- Tooltips inicializados con JavaScript
- Utilidades de spacing, color y flex (`mt-*`, `mb-*`, `bg-*`, `text-*`, `d-flex`, `justify-content-*`)

## Misión 2 – 🌮 La Cantina del Dev

Landing page para un restaurante temático para devs, también con Bootstrap 5.  
Incluye navegación adaptada al restaurante, promo del día, galería, carta de precios y flujo completo de reserva con modal de confirmación.

**Componentes y utilidades usadas:**

- Navbar con esquema de color distinto y botón de “Reservar ahora”
- Alert de promoción + breadcrumb de navegación
- Carousel manual (sin autoplay) con captions
- Cards de platos con imagen SVG (`card-img-top`) y badge de precio
- Tabla de menú con fila destacada usando clases contextuales
- Formulario de reserva con inputs `date`, `time`, `select`, `textarea` y validación
- Modal de confirmación de reserva (API JS `bootstrap.Modal`)
- Popover informativo sobre la promoción
- Tema personalizado con `data-bs-theme` y variables CSS (`--bs-primary`, `--bs-body-bg`)

## Publicación

El proyecto está publicado en GitHub Pages:

- GitHub Pages: **https://zakkdruzer.github.io/bootstrap-battle/**
