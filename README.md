# Ingecard Clone

> 💻 Página creada en proceso de aprendizaje de Astro, la página oficial se encuentra aquí: [Ingecard oficial](https://ingecard.netlify.app/). Todas las imágenes y recursos pertenecen a sus credores.

![just-the-basics](./readme-images/landing.png)

## 🚀 Estructura del proyecto

Dentro de la carpeta del proyecto se encuentra la siguiente estructura de archivos:

```text
/
├── public/
│   └── benefits/
│   |   └── ..imagenes-de-las-empresas.jpeg
│   └── images-de-la-ui.png...
├── src/
│   ├── components/
│   │   └── CTA.astro
│   │   └── Footer.astro
│   │   └── Header.astro
│   │   └── ElementoLista.astro
│   │   └── Ingecards.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
│       └── suscribete.astro
└── package.json
```

## 🧞 Instalación

Para clonar el proyecto, ejecuta el siguiente comando en tu terminal:

```bash
git clone https://github.com/geroxima/Ingecard-Clone.git

cd Ingecard-Clone/
```

Todos los comandos siguientes se ejecutan desde la carpeta raíz del proyecto.

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                            |
| `npm run dev`             | Inicia el servidor local en `localhost:4321`      |
| `npm run build`           | Construye el sitio estatico en producción en la carpeta `./dist/`          |
| `npm run astro -- --help` | Obtienes ayuda del CLI de astro                     |

