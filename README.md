<!-- Title -->
<h1 align='center' style="text-align:center; font-weight:bold; font-size:2.0em;letter-spacing:2.0px;">  Emergence of meta-stable clustering in mean-field transformer models </h1>

<p align='center' style="text-align:center;font-size:1.25em;">
    <a style="text-decoration: none;">Giuseppe Bruno<sup>1</sup></a>&nbsp;,&nbsp;
    <a style="text-decoration: none;">Federico Pasqualotto<sup>2</sup></a>&nbsp;,&nbsp;
    <a style="text-decoration: none;">Andrea Agazzi<sup>1</sup></a>&nbsp;&nbsp;
  <br>
<sup>1</sup>Department of Mathematics and Statistics, University of Bern&nbsp;&nbsp;&nbsp;
<br>
<sup>2</sup>Department of Mathematics, University of California, Berkeley&nbsp;&nbsp;&nbsp;
</p>


<p align='center';>
<b>
<em>ICLR 2025 Oral</em> <br>
</b>
</p>
<p align='center' style="text-align:center;font-size:2.5 em;">
<b>
    <a href="https://openreview.net/forum?id=eBS3dQQ8GV" target="_blank" style="text-decoration: none;">[Paper]</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/gbruno16/transformers-metastability" target="_blank" style="text-decoration: none;">[Code]</a>
</b>
</p>


## Abstract
We model the evolution of tokens within a deep stack of Transformer layers as a continuous-time flow on the unit sphere, governed by a mean-field interacting particle system, building on the framework introduced in Geshkovski et al. (2023). Studying the corresponding mean-field Partial Differential Equation (PDE), which can be interpreted as a Wasserstein gradient flow, in this paper we provide a mathematical investigation of the long-term behavior of this system, with a particular focus on the emergence and persistence of meta-stable phases and clustering phenomena, key elements in applications like next-token prediction. More specifically, we perform a perturbative analysis of the mean-field PDE around the iid uniform initialization and prove that, in the limit of large number of tokens, the model remains close to a meta-stable manifold of solutions with a given structure (e.g., periodicity). Further, the structure characterizing the meta-stable manifold is explicitly identified, as a function of the inverse temperature parameter of the model, by the index maximizing a certain rescaling of Gegenbauer polynomials.

## Citing

```bibtex
@article{bruno2024emergence,
  title={Emergence of meta-stable clustering in mean-field transformer models},
  author={Bruno, Giuseppe and Pasqualotto, Federico and Agazzi, Andrea},
  journal={arXiv preprint arXiv:2410.23228},
  year={2024}
}
```
