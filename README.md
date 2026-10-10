# exponencialesfirm.com

Código de [exponencialesfirm.com](https://exponencialesfirm.com), la web de **Exponenciales Firm**:
consultoría de CRM, automatización e IA para empresas B2B, y formación 1:1 en Claude Code.

## Cómo está hecha

- **HTML y CSS a mano**, sin frameworks ni paso de compilación. Cada página es un archivo.
- **Construida con [Claude Code](https://claude.com/claude-code)**: diseño, copy, maquetación,
  páginas legales, redirecciones y despliegue.
- **Publicada en Netlify.** Cada cambio en la rama `main` se despliega solo.

## Estructura

| Archivo | Qué es |
|---|---|
| `index.html` | Home: servicios, proyectos y contacto |
| `formacion.html` | Formación en Claude Code (1:1 y grupos reducidos) |
| `aviso-legal.html`, `politica-de-privacidad.html`, `politica-de-cookies.html` | Páginas legales (comparten `legal.css`) |
| `404.html` | Página de error |
| `_redirects` | Redirecciones 301 desde las URL de la web anterior (WordPress) |
| `netlify.toml` | Configuración del despliegue |
| `logos/` | Logotipos de clientes, propiedad de sus titulares |

## Sistema de diseño

Fondo casi negro, un solo color de acento (coral `#F43A59`), tipografía Geist y Geist Mono,
líneas finas e índices numerados. Sin degradados ni sombras.

## Verlo en local

Sirve la carpeta con cualquier servidor estático que resuelva URL sin extensión
(`/formacion` → `formacion.html`), por ejemplo `npx serve`.

---

© Juan José Lazcano. El código se publica como muestra de trabajo; los textos, la marca y los
logotipos no son de libre uso.
