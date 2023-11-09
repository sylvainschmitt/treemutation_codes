# Treemutation Codes

[![DOI](https://zenodo.org/badge/715065570.svg)](https://zenodo.org/doi/10.5281/zenodo.10090429)

 This repository contain all codes of the TreeMutation project and the analyses of Schmitt *et al.,* (in prep) PNAS (*to update)*:

* [genomeAnnotation](https://github.com/sylvainschmitt/genomeAnnotation/tree/c0493f536ab7d6915d9eed68a4288dc98a34112d): singularity & snakemake workflow to annotate genomes transposable elements (TE) and genes.
* [detectMutations - Angela](https://github.com/sylvainschmitt/detectMutations/tree/622498154103daccd6795b55362c1d88ca546303): singularity & snakemake workflow to detect mutation with Strelka2 in the *D. guianensis* tree.
* [detectMutations - Sixto](https://github.com/sylvainschmitt/detectMutations/tree/797b07d0757d77347ad9eca11532dab87baa2922): singularity & snakemake workflow to detect mutation with Strelka2 in the *S. rubra tree*.
* [detectMutations - fruits](https://github.com/sylvainschmitt/detectMutations/tree/252323eab5fbf994e09e11579338d462b2b5c707): singularity & snakemake workflow to detect mutation with GATK in the fruits of the *D. guianensis* and the *S. rubra* trees.
* [treemutation](https://github.com/sylvainschmitt/treemutation/tree/fc6a2eeef7b2bb1d178ebfbf3a79652ca13fb9df): R code for all the project and manuscript analyses.

```
git submodule add git@github.com:sylvainschmitt/genomeAnnotation.git
git submodule add -b angela --name detectMutations_angela git@github.com:sylvainschmitt/detectMutations.git detectMutations_angela
git submodule add -b sixto --name detectMutations_sixto git@github.com:sylvainschmitt/detectMutations.git detectMutations_sixto
git submodule add -b fruits --name detectMutations_fruits git@github.com:sylvainschmitt/detectMutations.git detectMutations_fruits
git submodule add git@github.com:sylvainschmitt/treemutation.git
```
