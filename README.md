# Luis Coding Inventory

Este proyecto consiste en una interfaz web para la gestión de inventario de equipos (hardware, mobiliario, etc.) con un diseño responsive y enfoque Mobile First.

## Estructura del Proyecto

```
project-folder/
│
├── css/
│   ├── variables.css  (CSS variables para theming)
│   ├── layout.css     (Estructuras de layout de página)
│   ├── components.css (Componentes reutilizables como botones)
│   ├── home.css       (Estilos específicos para la página de inicio)
│   ├── detail.css     (Estilos específicos para la página de detalle)
│   └── main.css       (Importa todos los archivos CSS)
│
├── img/              (Para imágenes de marcador de posición)
│   └── placeholder.jpg
│
├── home.html         (Página de listado de equipos)
├── detail.html       (Formulario para crear/editar equipos)
└── README.md         (Este archivo)
```

## Características

- **Diseño Responsive**: Adaptado a diferentes tamaños de pantalla con enfoque Mobile First
- **Arquitectura CSS Modular**: Organización de CSS en múltiples archivos para mejor mantenimiento
- **Variables CSS**: Uso de variables CSS para theming consistente
- **Componentes Reutilizables**: Botones, tarjetas, formularios, etc.
- **Navegación Adaptativa**: Menú lateral que se convierte en drawer en dispositivos móviles
- **Formularios Interactivos**: Con validación y previsualización de imágenes

## Páginas

### Home (home.html)

- Listado de equipos en formato de tarjetas
- Barra de búsqueda y filtros
- Paginación
- Acciones rápidas (editar, eliminar)

### Detalle (detail.html)

- Formulario para crear nuevos equipos
- Formulario para editar equipos existentes (detecta automáticamente el modo por URL)
- Carga de imágenes con previsualización
- Organización en secciones para mejor usabilidad

## Tecnologías Utilizadas

- HTML5
- CSS3 (Variables CSS, Flexbox, Grid)
- Font Awesome (para iconos)
- Google Fonts (Roboto)

## Cómo Usar

1. Simplemente abre el archivo `home.html` en tu navegador para ver la lista de equipos
2. Haz clic en "Nuevo Equipo" o en el botón de editar de cualquier equipo para ir al formulario
3. El formulario detectará automáticamente si estás en modo creación o edición

## Mejoras Futuras

- Implementar almacenamiento local para guardar los datos
- Añadir funcionalidad de búsqueda real
- Implementar filtrado dinámico
- Añadir animaciones y transiciones
- Integrar con una API backend

## Autor

Este proyecto fue creado como parte de un ejercicio de Keep Coding para el curso de HTML, por Luis Alberto Sanchez.