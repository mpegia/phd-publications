# Modalities and Representations in Media Retrieval

**PhD Thesis & Publications** · **[Maria-Eirini Pegia]** · [Reykjavik University / Department of Computer Science] · 2026

![Defense Date](https://img.shields.io/badge/Thesis%20Defense-Dec%204%2C%202026-blue)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=cMTMUBcAAAAJ&hl=el)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--2643--0028-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0003-2643-0028)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)

> **Note:** The full dissertation PDF and defense slides will be uploaded here following the public defense on **December 4, 2026**.

## Overview
This repository collects the dissertation, published papers, BibTeX citations, and open-source artifacts produced during my PhD research on **Modalities and Representations in Media Retrieval**.

## Abstract 
The rapid growth of diverse web content has shifted the primary challenge of media retrieval from data storage to effective retrieval across diverse media types. Multimedia assets are frequently accompanied by complex, spatiotemporal metadata that fundamentally alters how content is searched and interpreted, but existing literature frequently overlooks these relationships with most studies focusing heavily on isolated data content. This thesis addresses this gap by investigating the interactions between data modalities, structural representations and numerical embeddings across three distinct retrieval domains: Content-based Image Retrieval, 3D Object Retrieval and Text-to-Video Retrieval.

To evaluate these applications where real-world operational testing is constrained, this work relies on standardized dataset proxies: standard benchmarks and autonomous platform collections (aerial and underwater datasets) for image retrieval, computer-aided design (CAD) asset repositories for 3D object retrieval and web video and surveillance archives for text-to-video retrieval. Operating within these boundaries, the investigation explores how specific representation choices, modality selections and selective fusion strategies impact retrieval performance. Specifically, in the image domain, the thesis evaluates how feature distributions affect compact representations and integrates spatiotemporal metadata as standalone modalities. For 3D object retrieval, a comparative analysis of non-semantic, multi-representation geometric embeddings (view-based and mesh-based) is conducted to optimize fusion strategies. In the video domain, a comprehensive analysis is conducted to diagnose the performance plateau in text-to-video retrieval arising from complex multimodal interactions. Building on these structural findings, a semantically guided multimodal fusion method is introduced to improve linguistic-visual alignment and overcome these inherent retrieval limits. 

Empirically, our proposed **MuseHash** approach surpasses state-of-the-art methods in the Content-Based Image Retrieval domain with $\sim$4\% higher unimodal and $\sim$8\% higher multimodal mean average precision (mAP) at comparable query speeds. Although longer bit lengths increase memory demands and training overhead by up to $\sim$50\%, MuseHash consistently maintained the shortest training times among all evaluated hashing variants.

When applied to 3D Object Retrieval, MuseHash delivers $\sim$11\% unimodal and $\sim$9\% multimodal improvements alongside faster query times. While increased code lengths again lead to higher memory demands and up to a $\sim$50\% increase in training time over baselines due to complex computations, the MuseHash variant consistently maintains the shortest training time as the most computationally efficient option. 

Finally, in the video domain, our empirical and linguistic analysis diagnoses the text-to-video performance plateau by classifying text queries into varying complexity levels to reveal which linguistic structures present the greatest challenges. Building on these insights, our semantically guided framework improves overall recall ($R@k$) performance by 2–3\%, with gains of 6–7\% on complex, multi-category queries, while maintaining very low query overhead ($\sim$2 ms for unimodal and $\sim$4 ms for multimodal queries).

**Keywords:** Multimedia Information Retrieval, Multimodal Fusion Strategies, Structural Representations, Spatiotemporal Metadata, Content-Based Image Retrieval, 3D Object Retrieval, Text-to-Video Retrieval

### Cite This Thesis
```bibtex
@phdthesis{pegia2026modalities,
  title  = {Modalities and Representations in Media Retrieval},
  author = {Pegia, Maria-Eirini},
  school = {Reykjavik University},
  year   = {2026},
  month  = dec,
  url    = {[https://github.com/mpegia/phd-publications](https://github.com/mpegia/phd-publications)}
}
