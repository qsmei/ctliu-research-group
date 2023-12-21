---
title: "Information-incorporated sparse convex clustering for disease subtyping"
authors:
- Xiaoyu Zhang
- admin
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Bioinformatics, 7*(39)"
publication_short: ""

abstract:

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://academic.oup.com/bioinformatics/article/39/7/btad417/7210259
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---



## Abstract

**Motivation**  Heterogeneity in human diseases presents clinical challenges in accurate disease characterization and treatment. Recently available high throughput multi-omics data may offer a great opportunity to explore the underlying mechanisms of diseases and improve disease heterogeneity assessment throughout the treatment course. In addition, increasingly accumulated data from existing literature may be informative about disease subtyping. However, the existing clustering procedures, such as Sparse Convex Clustering (SCC), cannot directly utilize the prior information even though SCC produces stable clusters. 

**Results**：We develop a clustering procedure, information-incorporated Sparse Convex Clustering, to respond to the need for disease subtyping in precision medicine. Utilizing the text mining approach, the proposed method leverages the existing information from previously published studies through a group lasso penalty to improve disease subtyping and biomarker identification. The proposed method allows taking heterogeneous information, such as multi-omics data. We conduct simulation studies under several scenarios with various accuracy of the prior information to evaluate the performance of our method. The proposed method outperforms other clustering methods, such as SCC, K-means, Sparse K-means, iCluster+, and Bayesian Consensus Clustering. In addition, the proposed method generates more accurate disease subtypes and identifies important biomarkers for future studies in real data analysis of breast and lung cancer-related omics data. In conclusion, we present an information-incorporated clustering procedure that allows coherent pattern discovery and feature selection.

