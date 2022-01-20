<!--
This is a template for datasets in the Fatiando a Terra collection.

When adding a new dataset, fill out the information below. Search for all
instances of "CHANGEME" and replace with the relevant information.

You probably also want to edit the conda environment.yml file to give the
environment a new name and add/remove dependencies.

You can delete this comment once done.
-->

# Location - Data type

CHANGEME: A few sentences about the dataset and a plot should go here.

![CHANGEME: The alt text of the image.](preview.jpg)

| | Summary |
|--:|:--|
| File | `CHANGEME.csv` |
| Size | CHANGEME Mb |
| Version | [CHANGEME](https://github.com/fatiando-data/CHANGEME/releases/latest) |
| DOI | https://doi.org/CHANGEME |
| License | [CC-BY](https://creativecommons.org/licenses/by/4.0/) |
| MD5 | `md5:CHANGEME` |
| SHA256 | `sha256:CHANGEME` |
| Source | CHANGEME: Citation and/or link to original data source |
| Original license | CHANGEME: License (with link) of the original source |
| Processing code | [`prepare.ipynb`](https://nbviewer.org/github/fatiando-data/CHANGEME/blob/main/prepare.ipynb) |

## Changes made

> These are the changes made to the original dataset.

* CHANGEME: List here changes made to the original data.

## About this repository

This is a place to format and prepare the original dataset for use in our
tutorials and documentation.

We include the source code that prepares the datasets for redistribution by
filtering, standardizing, converting coordinates, compressing, etc.
The goal is to make loading the data as easy as possible (e.g., a single call
to `pandas.read_csv` or `xarray.load_dataset`).
Whenever possible, the code also downloads the original data (otherwise the
original data are included in this repository).

> 💡 **Tip:** The easiest way to download this dataset is using
> [Pooch](https://www.fatiando.org/pooch), particularly to download straight
> from the DOI of a release.

## Contributing

See our [Contributing Guidelines][contrib] for information on proposing new
datasets and making changes to this repository.

## License

All Python source code is made available under the BSD 3-clause license. You
can freely use and modify the code, without warranty, so long as you provide
attribution to the authors.

Unless otherwise specified, all data files and figures created by the code are
available under the Creative Commons Attribution 4.0 License (CC-BY).

See [`LICENSE.txt`](LICENSE.txt) for the full text of each license.

The license for the original data is specified in this `README.md` file.


[contrib]: https://github.com/fatiando-data/.github/blob/main/CONTRIBUTING.md
