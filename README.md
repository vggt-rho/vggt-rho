# VGGT-ρ anonymous project page

Static English project page for “VGGT-ρ: Accelerating Visual Geometry Inference via Adaptive View Selection”. Open `index.html` directly, or serve this directory:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

The page works without JavaScript, a build step, external fonts, analytics, or embedded third-party media. All displayed assets are local. Navigation links lead to page sections; figure links open full-size images.

## Content source

Text and numerical results follow `../template/iclr2027_conference.tex`, as read on 2026-09-26. The five PNG figures are browser-ready renderings of the matching PDFs in `../template/figures/`; the scientific panels and values are unchanged. These web assets are display exports, not new experimental evidence. Result tables retain the manuscript's units, precision, evaluation domains, and timing distinctions.

To refresh an image from this directory, use the corresponding PDF stem:

```sh
pdftoppm -f 1 -singlefile -scale-to 2400 -png ../template/figures/fig_01_method_overview.pdf static/images/fig_01_method_overview
```

## Anonymous release

The page identifies the authors as “Anonymous Authors”. Author names, affiliations, email addresses, personal profiles, lab-related links, identifying metadata, sample media, the sample PDF, and the template portrait favicon have been removed. No manuscript source, paper PDF, code repository, arXiv link, or author-bearing citation is distributed here. Search indexing is discouraged through the robots meta tag; this is not access control.

Publish only this directory using an anonymous hosting account and URL. Before adding a paper, supplementary file, or new media, inspect its visible content and embedded metadata for author or institution identifiers. Hosting account information and domain ownership are outside the static page.

## Template attribution

The page was adapted from the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), itself based on [Nerfies](https://nerfies.github.io/). These are third-party template credits, not research-author affiliations. The template is licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). The content, layout, styles, and assets have been modified for this anonymous project page.
