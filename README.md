# Aamir Sohaib — Financial Analysis & Data Analytics

**Live website:** https://aamir-portfolio-teal.vercel.app

A responsive portfolio presenting professional finance experience, independent financial research, data analytics, and graduate machine learning experiments.

## Pages

- `index.html`: introduction, selected projects, expertise, career history, education and contact.
- `delta.html`: operational and financial intelligence case study, dashboard artifacts and SQL excerpt.
- `rbc.html`: independent equity research process and limitations.
- `machine-learning.html`: IMDB sentiment classification, nine neural-network experiments in R/Keras, and validation-led model evaluation.
- `resume.html`: accessible résumé with print-to-PDF support.

## Run locally

```sh
npm run dev
```

Open http://localhost:3000. No package installation is needed.

## Build

```sh
npm run build
```

The dependency-free build copies the static pages and assets into `dist/`.

## Vercel

Import this repository into Vercel using the Other framework preset. The included configuration runs `npm run build` and serves `dist/`.

## Content and provenance

Professional history and education are based on the supplied LinkedIn profile. Project content and visuals are drawn from the author's public repositories:

- https://github.com/roceye1/Delta-Operational-Intelligence
- https://github.com/roceye1/RBC_RY_Eq_research
- https://github.com/roceye1/811424116_AdvancedMachineLearning

The résumé is also available as a downloadable PDF.

No affiliation with Delta Air Lines or Royal Bank of Canada is implied. Academic experiments are distinguished from professional work; reported metrics are historical recorded results. The Research Notebook theme uses a custom generated editorial illustration in the hero, not a real workplace photograph. Delta and RBC feature actual dashboard/report previews. The ML case study covers Assignment 1 IMDB dense neural networks in R and Keras; metrics are drawn from the executive summary report. Uncontextualized employment percentage achievements have not been included.

Third-party data and project artifacts retain their original attribution and applicable rights. No blanket license is asserted.

## Editing

Edit the HTML pages directly; shared presentation lives in `styles.css` and `notebook.css`, navigation and résumé printing in `script.js`. Rebuild after updates. Contact links use the email and LinkedIn address from the supplied profile. No analytics tracking or contact-form database is installed.
