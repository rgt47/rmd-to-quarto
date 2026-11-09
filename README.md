# Transitioning from R Markdown to Quarto: A One-Week Boot Camp
*2026-07-28 19:40 PDT*

A short workshop for analysts who already write R Markdown and
wish to move their work to Quarto. Five days, one chapter each.

## Structure

- **Day 1** From R Markdown to Quarto, Your First Render
- **Day 2** Document Anatomy: YAML, Chunks, and the Execution
  Model
- **Day 3** Output Formats, Figures, Tables, and
  Cross-References
- **Day 4** Projects at Scale: Websites, Books, and
  Manuscripts
- **Day 5** Reproducibility, Publishing, and Migrating a Real
  Project

Each day is approximately 1 hour of lecture content + 2 hours
of homework with worked solutions. No examinations.

## Build

```bash
quarto render
```

The cover is generated procedurally:

```bash
Rscript images/build-cover.R
```

## Position in the series

This workshop is the Quarto transition volume in the rgtlab
curriculum sequence. It follows the two preparatory boot camps
and feeds the reproducibility and infrastructure volumes:

- *R for Biostatistics*: preparatory R
- *Git and GitHub for Biostatistics*: preparatory version
  control
- *Biostatistics Practicum*: workflow infrastructure (Git in
  depth, Docker, renv, Quarto, CDISC)
- *Reproducible Research for the Health Sciences*: the
  reproducibility core

## License

Prose: CC BY 4.0. Code samples: MIT. Repository code: GPL-3.
