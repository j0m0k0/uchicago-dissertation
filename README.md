[![Overleaf Template](https://img.shields.io/badge/Overleaf-Template-success?logo=overleaf)](https://www.overleaf.com/latex/templates/university-of-chicago-phd-dissertation-template/syvxgkqhvqqt)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/k4rtik/uchicago-dissertation)](https://github.com/k4rtik/uchicago-dissertation/releases)

UChicago PhD Dissertation LaTeX Class & Template
================================================

This repository includes a LaTeX class and template for
correctly formatted electronic Ph.D. dissertations at the University of Chicago.

The [official format specification][spec] can be tough to meet from scratch.
That's why we are providing this class and template. The class, when properly
used as in the template, will make sure your dissertation meets the spec.

[spec]: https://www.lib.uchicago.edu/research/scholar/phd/dissertation-requirements/format/ "University-Wide Requirements for the Ph.D. Dissertation > Format"

Get Started
===========

1. Get your LaTeX environment set up.
2. Download `thesis_template.tex` and `ucetd.cls`.
3. Open `thesis_template.tex`, look around, and start writing!

Alternatively, the template is also available from [Overleaf](https://www.overleaf.com/latex/templates/university-of-chicago-phd-dissertation-template/syvxgkqhvqqt).

Committee Information
---------------------

The title page now supports committee details in addition to the existing
metadata. Set the chair, optional co-chair, and committee members in your
document preamble using the following commands:

```tex
\chair{Ada Lovelace}
\cochair{Alan Turing} % optional
\committeeMember{Grace Hopper}
\committeeMember{Katherine Johnson}
% or provide a comma-separated list in a single command
\committeeMembers{Claude Shannon, Donald Knuth}
```

Any number of `\committeeMember` commands may be used. If `\cochair` is not
provided it will be omitted from the title page automatically.
