---
title: "Variational formulations of ODE-Net as a mean-field optimal control problem and existence results"
authors:
- admin
- Mizuho Okumura
date: "2022-03-09T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2303.05924"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: This paper presents a mathematical analysis of ODE-Net, a continuum model of deep neural networks (DNNs). In recent years, Machine Learning researchers have introduced ideas of replacing the deep structure of DNNs with ODEs as a continuum limit. These studies regard the "learning" of ODE-Net as the minimization of a "loss" constrained by a parametric ODE. Although the existence of a minimizer for this minimization problem needs to be assumed, only a few studies have investigated its existence analytically in detail. In the present paper, the existence of a minimizer is discussed based on a formulation of ODE-Net as a measure-theoretic mean-field optimal control problem. The existence result is proved when a neural network, which describes a vector field of ODE-Net, is linear with respect to learnable parameters. The proof employs the measure-theoretic formulation combined with the direct method of Calculus of Variations. Secondly, an idealized minimization problem is proposed to remove the above linearity assumption. Such a problem is inspired by a kinetic regularization associated with the Benamou--Brenier formula and universal approximation theorems for neural networks. The proofs of these existence results use variational methods, differential equations, and mean-field optimal control theory. They will stand for a new analytic way to investigate the learning process of deep neural networks.

# Summary. An optional shortened abstract.
summary: This paper gives formulation and justification of Deep Learning from the continuous view point.

tags:
- ODE-Net
- Calculus of Variations & Optimal Control
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2303.05924
url_pdf: https://arxiv.org/pdf/2303.05924.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
