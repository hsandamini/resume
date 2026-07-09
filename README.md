# Hiruni Sandamini — CV

LaTeX source for my CV/resume.

## Files

- `cv.tex` — main resume content
- `main.tex` — entry point document
- `resume.cls` — custom resume class used for formatting

## How to compile

### Option 1: Overleaf (recommended, no installation needed)
1. Create a new blank project on Overleaf
2. Upload all three files (`cv.tex`, `main.tex`, `resume.cls`)
3. Set the correct file as the main document and click Recompile

### Option 2: Locally
If you have a LaTeX distribution installed (e.g. TeX Live or MacTeX):

pdflatex main.tex

You may need to run it twice for links and references to resolve correctly.

### Fonts / packages required
This document uses the `fontawesome` package for icons (phone, email, globe, map marker). If compiling locally, install it via:

tlmgr install fontawesome

## License
Personal CV content — not intended for reuse as-is, but feel free to fork the structure for your own resume.
