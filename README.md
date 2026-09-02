# llatoski.github.io

Personal academic site for Luís Carlos Fagundes Latoski — physicist, nonequilibrium
statistical mechanics, Instituto de Física, UFRGS.

Single static page. No build step: `index.html` carries its own CSS and JavaScript,
fonts are self-hosted latin subsets, and the hero runs a small persistent-voter-model
simulation on a lattice (canvas, capped at 30 fps, paused off-screen, one static frame
under `prefers-reduced-motion`). The page is fully readable with JavaScript disabled.

```
index.html            the page
cv.pdf                curriculum vitae
og.png                social preview, built from the same simulation
favicon.svg/.png      a domain interface on an 8x8 lattice
fonts/                Newsreader, IBM Plex Sans, IBM Plex Mono (subset, OFL)
robots.txt sitemap.xml
```

Content source of truth: `Academics/Profile/` in the author's working tree.
