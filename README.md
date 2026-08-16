# IC1400 — Tema 10: Rendimiento de Memoria

Revisión sistemática para el curso **IC-1400 Fundamentos de Organización de Computadoras**.

## Tema

**Análisis del tiempo de acceso y rendimiento de diferentes tecnologías de memoria.**

## Integrantes

- Víctor Julio Chavarría Ordoñez
- Luiz Fernando Mendoza Contreras
- Harold Philippe Umaña Pacheco

Escuela de Computación — Ingeniería en Computación — Tecnológico de Costa Rica.

## Estructura del repositorio

- `main.tex`: archivo principal del artículo IEEE.
- `referencias.bib`: bibliografía en formato BibTeX.
- `secciones/`: contenido dividido para trabajar en paralelo.
- `figuras/`: imágenes, diagramas y gráficas utilizadas en el artículo.
- `.github/workflows/latex.yml`: compilación automática con GitHub Actions.

## Trabajo colaborativo

Para reducir conflictos, cada integrante puede trabajar en archivos de sección distintos. Quien prefiera no usar Git por terminal puede editar los archivos `.tex` directamente desde GitHub en el navegador y guardar los cambios con **Commit changes**.

## Compilación local

Con una distribución de LaTeX y `latexmk` instalados:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

Para limpiar archivos auxiliares:

```bash
latexmk -c
```

GitHub Actions también intenta compilar `main.tex` automáticamente en cada `push` y `pull_request`.
