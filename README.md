# rapids-singlecell notebooks

This repository houses the notebooks from [rapids-singlecell](https://rapids-singlecell.readthedocs.io/en/latest/)

The notebooks use the Scanpy 1.13 `use`/`out` API with `from anndata.acc import A`
and require a RAPIDS-singlecell build with the corresponding accessor support
(0.19 development version). `use` selects the input, and `out` selects the output
location; omitted arguments retain the default locations. For example,
`use=A.layers["counts"]` reads a layer and `out=A.obsm["X_umap_harmony"]`
stores an embedding. See the [RAPIDS-singlecell release notes](https://rapids-singlecell.scverse.org/en/latest/release-notes/index.html).

[//]: # (numfocus-fiscal-sponsor-attribution)

rapids_singlecell-notebooks is part of the scverse® project ([website](https://scverse.org), [governance](https://scverse.org/about/roles)) and is fiscally sponsored by [NumFOCUS](https://numfocus.org/).
If you like scverse® and want to support our mission, please consider making a tax-deductible [donation](https://numfocus.org/donate-to-scverse) to help the project pay for developer time, professional services, travel, workshops, and a variety of other needs.

<div align="center">
<a href="https://numfocus.org/project/scverse">
  <img
    src="https://raw.githubusercontent.com/numfocus/templates/master/images/numfocus-logo.png"
    width="200"
  >
</a>
</div>
