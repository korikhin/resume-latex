# Resume $`\LaTeX`$

A minimalist resume template designed to be simple, readable, and reliable. It is one-page oriented and uses an **ATS-friendly** layout with no tables, and no columns. The template allows easy customization of sections and spacing.

See the [example](example.pdf).

## Quick Start

Build using [Tectonic](https://github.com/tectonic-typesetting/tectonic "Tectonic (GitHub)"):

```sh
tectonic -X compile src/main.tex --outdir build \
    --keep-intermediates \
    --only-cached \
    --keep-logs \
    --synctex
```

This will generate `main.pdf` file in `build` directory.
