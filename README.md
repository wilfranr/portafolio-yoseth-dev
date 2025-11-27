# Portafolio Yoseth Dev

Portafolio personal desarrollado con HTML, Tailwind CSS y JavaScript vanilla.

## Características

- Diseño responsive y moderno
- Modo oscuro/claro
- Animaciones y transiciones suaves
- Minijuego interactivo (Memory Match)
- Chat con IA integrado (Gemini API)
- Secciones: Home, Skills, Proyectos, Contacto

## Tecnologías

- HTML5
- Tailwind CSS (CDN)
- JavaScript Vanilla
- Lucide Icons
- Google Fonts (Inter, JetBrains Mono)

## Deployment en GitHub Pages

### Opción 1: Deployment Automático (Recomendado)

Este repositorio está configurado con GitHub Actions para deployment automático. Solo necesitas:

1. Subir el código a GitHub:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/portafolio-yoseth-dev.git
git push -u origin main
```

2. Habilitar GitHub Pages en tu repositorio:
   - Ve a Settings > Pages
   - En "Source", selecciona "GitHub Actions"
   - El workflow se ejecutará automáticamente en cada push

### Opción 2: Deployment Manual

1. Ve a Settings > Pages en tu repositorio de GitHub
2. En "Source", selecciona la rama `main` y la carpeta `/ (root)`
3. Guarda los cambios
4. Tu sitio estará disponible en: `https://TU_USUARIO.github.io/portafolio-yoseth-dev/`

## Configuración Local

No requiere instalación. Simplemente abre `index.html` en tu navegador o usa un servidor local:

```bash
# Con Python
python -m http.server 8000

# Con Node.js (http-server)
npx http-server

# Con PHP
php -S localhost:8000
```

## Notas

- El chat con IA requiere una API key de Gemini. Actualmente está vacía en el código.
- Para usar el chat, agrega tu API key en la línea 920 del `index.html`:
  ```javascript
  const apiKey = "TU_API_KEY_AQUI";
  ```

## Licencia

Este proyecto es de uso personal.

