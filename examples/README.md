# Examples: Real Academic Paper Conversions

This directory contains real conversion examples showing paper2md output on actual arXiv papers.

---

## Example 1: ResNet — Deep Residual Learning for Image Recognition

**Source:** [arXiv:1512.03385](https://arxiv.org/abs/1512.03385) — He, Zhang, Ren, Sun (Microsoft Research, 2015)  
**Document:** 12 pages, double-column layout, 79 equations, 15 tables, 10 figures

### Stats

| Metric | Result |
|--------|--------|
| Formulas converted | 79 |
| Rendering errors | **0** |
| Tables | 15 |
| Figures extracted | 10 |
| Processing time | ~20 seconds |

### Sample Formula

**Original PDF (garbled text extraction):**
```
F(x) = H(x) - x
```

**paper2md output** — Markdown source:
```
$$
\mathcal{F}(\mathbf{x}) = \mathcal{H}(\mathbf{x}) - \mathbf{x}
$$
```

**Rendered** (GitHub / Obsidian / KaTeX):

$$
\mathcal{F}(\mathbf{x}) = \mathcal{H}(\mathbf{x}) - \mathbf{x}
$$

The residual learning formulation — preserved exactly, renders in Obsidian without errors.

### Sample Table (ImageNet Results)

**Rendered GFM table:**

| Model | top-1 err. | top-5 err. | Parameters |
|-------|-----------|-----------|------------|
| VGG-16 | 28.07 | 9.33 | 138M |
| ResNet-34 | 25.03 | 7.76 | 21.8M |
| ResNet-50 | 22.85 | 6.71 | 25.6M |
| ResNet-101 | 21.75 | 6.05 | 44.5M |
| ResNet-152 | **21.43** | **5.71** | 60.2M |

---

## Try It Yourself

Any public arXiv paper works. Suggested test papers that showcase formula/table density:

| Paper | arXiv ID | Why it's a good test |
|-------|----------|----------------------|
| ResNet | 1512.03385 | Dense equations, complex tables |
| Attention Is All You Need | 1706.03762 | Multi-head attention formulas, architecture tables |
| BERT | 1810.04805 | Many ablation tables |
| GPT-3 | 2005.14165 | Very long paper, many results tables |
| Denoising Diffusion | 2006.11239 | Score-function equations |

**→ [Start converting at paper2md.com](https://paper2md.com)**
