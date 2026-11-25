# Ingeniería estructural abierta

Página común de cuatro programas libres para ingeniería estructural, publicada en
**https://marcel1983.github.io** (español) y **https://marcel1983.github.io/en/**
(inglés):

- [IngeCalc](https://github.com/marcel1983/ingecalc): hojas de cálculo de ingeniería documentadas.
- [OpenConex](https://github.com/marcel1983/openconex): diseño de conexiones de acero según AISC.
- [OpenFEMConex](https://github.com/marcel1983/openfemconex): placas base con elementos finitos (CalculiX).
- [OpenSees Studio](https://github.com/marcel1983/opensees-studio): interfaz gráfica para OpenSees.

Incluye la guía para descargar e instalar los programas, reportar problemas con
las plantillas de cada repositorio y participar sin programar.

## Estructura

- `index.html`: la página en español (HTML, CSS y JavaScript en un solo archivo).
- `en/index.html`: la misma página en inglés. Usa las imágenes de `img/` con
  rutas `../img/`. Un cambio de contenido se hace en las dos.
- `img/`: capturas de los programas, y `og.png` y `og-en.png`, las imágenes que
  muestran LinkedIn, WhatsApp y otras redes al compartir cada enlace.
- `.nojekyll`: GitHub Pages sirve los archivos tal cual, sin Jekyll.

Para editar la descripción de un programa, cambia la lista `apps` al final de
cada `index.html`; para la tabla de descargas, la lista `dl`.
