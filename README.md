# ✨ ProyectoFinal-HTML-CSS-TAREA ✨

_Último trabajo de **Conquer Blocks** de **CSS** y **HTML**, ¡muchas gracias por seguirme hasta aquí!!_ 🦢📂

---

## 📄 Descripción del proyecto

Quinta tarea entregable de **CSS**. El ejercicio consiste en **completar al máximo el proyecto del módulo de HTML** y darle estilos siguiendo los mismos requerimientos que en las entregas anteriores.

Como no hay Figma para este proyecto, el diseño queda a *imaginación propia*: la idea es que sea un proyecto **lo más real posible**, como si fuera para un **cliente final**. 🎯

El resultado es una web para **Conquer Blocks**, una academia online de programación en español. La paleta de colores (naranja y amarillo sobre azul oscuro) sale del logotipo de la academia.

> ⚠️ _Proyecto de aprendizaje inspirado en Conquer Blocks. No es la web oficial de la academia._

---

## 📌 Requerimientos

- ✅ **Boilerplate:** partí de mi proyecto de HTML como punto de partida.
- ✅ **Uso de SASS:** el código está organizado en parciales SCSS (`scss/`) y se compila a `styles.css`.
- ✅ **Recursos de diseño:** no hay fichero de Figma en esta entrega; el diseño es propio.
- ✅ **Iconos en SVG:** las ilustraciones están en formato **SVG** en lugar de imágenes rasterizadas (solo el logotipo es PNG).
- ✅ **Semántica:** uso de `header`, `nav`, `main`, `section`, `article`, `footer`, `time`, etc.
- ✅ **Interactividad:** botones, enlaces, tarjetas y campos de formulario tienen su **estado hover** (y `focus`).
- ✅ **Responsive:** maquetado **mobile first**, empezando desde móvil hacia arriba con **media queries** (`768px` y `1024px`).

---

## 📂 Estructura del proyecto

```text
ProyectoFinal CB (Tarea)/
├── images/              # Logotipo e ilustraciones SVG
├── scss/
│   ├── _variables.scss  # Colores, tipografía, breakpoints y mixin
│   ├── _base.scss       # Reset y estilos globales
│   ├── _layout.scss     # Cabecera, pie, rejillas y tarjetas
│   ├── _components.scss # Botones, hero, formularios, listas
│   └── main.scss        # Archivo principal que importa los parciales
├── styles.css           # CSS compilado desde SCSS
├── index.html
├── quienes-somos.html
├── cursos.html
├── detalle-curso.html
├── blog.html
├── detalle-noticia.html
├── registro.html
├── login.html
├── contacto.html
├── aviso-legal.html
├── package.json
├── LICENSE              # Licencia MIT
└── README.md
```

---

## 🗂️ Páginas de la web

| Página | Archivo | Contenido |
| --- | --- | --- |
| 🏠 Home | `index.html` | Hero, objetivo, quiénes somos, últimos cursos y noticias |
| 👥 Quiénes somos | `quienes-somos.html` | Sobre la academia, misión y equipo |
| 📚 Cursos | `cursos.html` | Listado de cursos (Frontend, Backend, Full Stack) |
| 🎓 Detalle de curso | `detalle-curso.html` | Descripción, temario y requisitos |
| 📰 Blog | `blog.html` | Últimas publicaciones |
| 📝 Detalle de noticia | `detalle-noticia.html` | Artículo completo |
| 🧾 Registro | `registro.html` | Formulario de alta con varios tipos de campo |
| 🔐 Login | `login.html` | Inicio de sesión |
| ✉️ Contacto | `contacto.html` | Datos, mapa de Google y formulario |
| ⚖️ Aviso legal | `aviso-legal.html` | Información legal |

---

## 🎨 Diseño y estilos

- **Colores:** naranja `#ff5a1f`, amarillo `#ffb300` y azul oscuro `#14162b`, con degradado naranja-amarillo como en el logotipo.
- **Tipografía:** pila de fuentes del sistema (`Segoe UI`, `Roboto`, `Arial`...).
- **Cabecera fija** (`sticky`) con navegación en forma de píldoras.
- **Tarjetas** con sombra que se elevan al pasar el ratón.
- **Rejillas** de 1 columna en móvil, 2 en tablet y 3 en escritorio (`CSS Grid`).
- **Formularios** con estados `hover` y `focus` visibles.

---

## 🚀 Cómo usarlo

1. Clona el repositorio y abre `index.html` en el navegador.
2. Si quieres modificar los estilos, instala las dependencias y compila SCSS:

```bash
npm install
npm run sass     # compila una vez
npm run watch    # compila al guardar
```

---

## 📦 Entrega

- 📌 **Repositorio:** repositorio específico para este proyecto.
- 📌 **Enlace público:** subida a **GitHub Pages** _(pendiente de publicar)_.

---

## 🛠️ Tecnologías

**HTML5** · **CSS3** · **SCSS/SASS** · **SVG** · **Git & GitHub**

---

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**. Consulta el archivo [LICENSE](./LICENSE) para más información. ✅

---

_Hecho con ❤️ y mucho café por **valentinoaguiarhirales1-art**_ ✨
