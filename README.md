# Portfolio de jmadasme

Catálogo personal de proyectos de electrónica, IoT, software y docencia. Cada proyecto conserva **todas sus versiones históricas** dentro de `versions/`, no solo la última.

**Sitio publicado:** <https://jmadasme.github.io/>

---

## Tres secciones

| Sección | Proyectos | Qué encontrarás |
|---|---:|---|
| **Arduino UNO Q** | 2 | Cursos y librerías de Arduino, ESP32 y sensores |
| **IoT & Hardware** | 4 | LoRaWAN, Node-RED, CashDro y autoatención |
| **Software & IA** | 3 | Licitaciones públicas, cursos y utilidades Python |

## Proyectos

| Proyecto | Versiones | Sección |
|---|---:|---|
| `academia-arduino` | 4 | Arduino UNO Q |
| `yl69-soil-moisture` | 1 | Arduino UNO Q |
| `hospital-lorawan` | 1 | IoT & Hardware |
| `nodered-lab` | 1 | IoT & Hardware |
| `cashdro-params` | 1 | IoT & Hardware |
| `autoatencion` | 3 | IoT & Hardware |
| `licitaciones-mercado-publico` | 1 | Software & IA |
| `cursos-programacion` | 2 | Software & IA |
| `utilidades-python` | 4 | Software & IA |

**Total: 9 proyectos · 18 versiones · 3 secciones.**

## Cómo está construido

- Sitio estático, sin backend ni base de datos.
- Portada general con tres portales; cada portal abre su propio catálogo.
- Cada proyecto tiene su GitHub Page independiente, con:
  - hero y resumen ejecutivo;
  - problema y solución;
  - arquitectura y decisiones;
  - **catálogo de versiones** con enlace a la carpeta exacta del repositorio;
  - documentación (`datasheet`, `developer`, `REFERENCES`, bitácora);
  - sección **Comunidad** con FAQ y una moneda anónima persistente;
  - CTA “¿Te animás?”.
- Paleta sobria de azul petróleo: `#06141b`, `#0b222b`, `#2A9D8F`, `#457B9D`, `#5B7C99`.
- Sin frameworks de frontend: HTML, CSS y JavaScript del navegador.
- Gráficos e imágenes Open Graph generados como SVG y PNG.

## Estructura del repositorio

```text
.
├── index.html
├── arduino-unoq/
├── iot/
├── software/
├── assets/
│   ├── og.png
│   └── og.svg
├── .nojekyll
├── README.md
└── LICENSE
```

Cada página de sección enlaza a los repositorios y a las GitHub Pages de los proyectos. Las páginas de proyecto viven en el repositorio de cada proyecto, bajo `docs/`.

## Publicación

El sitio se publica con GitHub Pages desde la rama `main`, carpeta raíz. Los proyectos se publican desde `main` + `/docs`.

## Licencia

MIT © 2026 jmadasme. Cada proyecto conserva su propia licencia y la de sus dependencias.
