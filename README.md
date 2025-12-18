# Agency - Minimal Landing Page
Landing page moderna y minimalista para una agencia creativa. Diseño clean con animaciones suaves y un enfoque en la experiencia de usuario.

<img width="810" height="865" alt="image" src="https://github.com/user-attachments/assets/6fb5e42e-2f46-43c2-b332-7ead56cff7af" />
<img width="846" height="604" alt="image" src="https://github.com/user-attachments/assets/9f91b2b2-4f50-4050-b168-0aed04ef8834" />
<img width="995" height="662" alt="image" src="https://github.com/user-attachments/assets/9b147c7b-4540-4d6b-8a7e-f86393a4485e" />
<img width="974" height="758" alt="image" src="https://github.com/user-attachments/assets/4661da7b-c94b-4f88-912d-a87607f07180" />
<img width="616" height="750" alt="image" src="https://github.com/user-attachments/assets/37c771f3-3916-42e8-915c-7e911da8ede0" />


## Deploy Link
https://maryhug.github.io/NexCent/

## ✨ Características

- Diseño minimalista y profesional
- Totalmente responsive (móvil, tablet y desktop)
- Animaciones y transiciones suaves
- Secciones optimizadas para conversión
- Navegación fija con scroll suave
- Grid layout moderno con CSS Grid y Flexbox
- Paleta de colores personalizable mediante variables CSS

## 🚀 Secciones

- **Hero**: Presentación principal con estadísticas destacadas
- **About**: Información sobre la agencia con características clave
- **Services**: Grid de 6 servicios ofrecidos
- **Portfolio**: Galería de proyectos con overlay interactivo
- **Testimonials**: Testimonios de clientes
- **CTA**: Call-to-action para contacto
- **Footer**: Información de contacto y enlaces

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Google Fonts (Inter & Poppins)
- SVG para iconografía

## 📁 Estructura del Proyecto

```
agency-landing/
│
├── index.html          # Archivo HTML principal
├── styles.css          # Estilos CSS
├── assets/             # Carpeta de recursos
│   ├── hero-image.svg
│   ├── about-image.svg
│   ├── project-1.svg
│   ├── project-2.svg
│   ├── project-3.svg
│   └── cliente-1.svg
└── README.md
```

## 🎯 Instalación y Uso

1. Clona o descarga el repositorio
2. Crea la carpeta `assets/` y agrega las imágenes necesarias
3. Abre `index.html` en tu navegador

```
# Si usas un servidor local
npx serve .
# o
python -m http.server 8000
```

## 🎨 Personalización

### Colores

Modifica las variables CSS en `styles.css`:

```
:root {
    --primary-color: #000000;
    --accent-color: #6C5CE7;
    --text-primary: #000000;
    --text-secondary: #666666;
    --text-light: #999999;
    --bg-white: #FFFFFF;
    --bg-light: #ea96b5;
    --bg-gray: #FAFAFA;
    --border-color: #E5E5E5;
}
```

### Contenido

Edita el texto directamente en `index.html` para personalizar:
- Nombre de la agencia
- Servicios ofrecidos
- Información de contacto
- Estadísticas y testimonios

## 📱 Responsive Design

El diseño se adapta a tres breakpoints principales:
- Desktop: > 1024px
- Tablet: 768px - 1024px
- Mobile: < 768px
