# ☕ Maison Café

Landing page de una cafetería ficticia construida con Astro y Tailwind CSS.

🔗 **[Ver demo en vivo](https://maisoncafe.vercel.app)**

---

## 📸 Vista Previa

> Una landing page moderna con menú de bebidas, sección about, contacto y mapa de ubicación.

---

## 🛠️ Tech Stack

![Astro](https://img.shields.io/badge/Astro-black?style=for-the-badge&logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-black?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-black?style=for-the-badge&logo=javascript&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-black?style=for-the-badge&logo=vercel&logoColor=white)

---

## ✨ Features

- 🧭 Navbar con scroll suave hacia secciones
- ☕ Sección de menú completo con precios
- 📖 Sección "Nosotros" con historia de la cafetería
- 📍 Sección de ubicación y horarios
- 📬 Formulario de contacto
- 📱 Diseño completamente responsive

---

## 🚀 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/mfrann/maison-cafe.git
cd maison-cafe

# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm dev
```

Abre [http://localhost:4321](http://localhost:4321) en tu navegador.

---

## 🧞 Comandos

| Comando          | Acción                                       |
| ---------------- | -------------------------------------------- |
| `pnpm install`   | Instala las dependencias                     |
| `pnpm dev`       | Inicia el servidor local en `localhost:4321` |
| `pnpm build`     | Genera el build de producción en `./dist/`   |
| `pnpm preview`   | Previsualiza el build localmente             |

---

## 📁 Estructura del Proyecto

```
/
├── public/
│   └── assets/              # Imágenes y recursos estáticos
├── src/
│   ├── components/
│   │   ├── Header.astro     # Navbar principal
│   │   └── MenuCard.astro   # Tarjeta de ítem del menú
│   ├── layouts/
│   │   ├── About.astro      # Sección "Nosotros"
│   │   ├── Features.astro   # Sección de características
│   │   ├── Footer.astro     # Pie de página
│   │   ├── Hero.astro       # Sección principal / hero
│   │   ├── Map.astro        # Sección de ubicación y contacto
│   │   └── Menu.astro       # Sección del menú
│   ├── pages/
│   │   └── index.astro      # Página principal
│   └── styles/
│       └── global.css       # Estilos globales
├── astro.config.mjs
└── package.json
```

---

## 📄 Licencia

Este proyecto es de uso educativo y personal.

---

<div align="center">
  Hecho con ☕ por <a href="https://github.com/mfrann">mfrann</a>
</div>
