![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3964240.svg)

> *Cite this repository:*
>
> Debabrata Acharya. (2020, July 28). kalyaniuniversity/scRNA-seq-datasets: Publicly available Single-Cell RNA Sequencing Datasets (Version 0.1). Zenodo. http://doi.org/10.5281/zenodo.3964240

# scRNA-seq-datasets
A list of publicly available Single Cell RNA Sequencing datasets with proper attribution and associated toolkits.

## LICENSE
**Please note that even though this repository is free to use and modify under MIT License, but the individual datasets referenced here may be conducted under their own licencing terms.**

## Datasets
If we are keeping a copy of the dataset with this repository, it shall be available in the `datasets` folder within the named repository. Please check the reference table below to find whether we keep a copy of the dataset under the `Dataset` tab.

## Toolkit
If we have written a toolset for a certain dataset, it shall be available under the `toolkit` folder within the named repository. Please check the reference table below to find whether a certain dataset has any associated toolset under the `Tools` tab. Note that some of the preprocessing has also been done using our own preprocessing library `pytoolkit` available at [kalyaniuniversity/pytoolkit](https://github.com/kalyaniuniversity/mgx-datasets).

## REFERENCE TABLE

<table>
	<thead>
		<tr>
			<th colspan="6">scRNA-seq Dataset Reference Table</th>
		</tr>
		<tr>
			<th>Sl. No.</th>
			<th>Name</th>
			<th>Reference</th>
			<th>Dataset</th>
			<th>Tools</th>
			<th>Notes</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>1</td>
			<td>BMMC-AML</td>
			<td>Zheng, G. X., Terry, J. M., ... Gregory, M. T. (2017). <a href="https://www.nature.com/articles/ncomms14049" target="_blank">Massively parallel digital transcriptional profiling of single cells</a>. Nature communications, 8, 14049.</td>
			<td><a href="https://github.com/kalyaniuniversity/scRNA-seq-datasets/tree/master/BMMC-AML/datasets" target="_blank">BMMC-AML</a></td>
			<td><a href="https://github.com/kalyaniuniversity/pytoolkit" target="_blank">kalyaniuniversity/pytoolkit</a></td>
			<td>
				Bone marrow mononuclear cells with AML (2017), from <a href="https://support.10xgenomics.com/single-cell-gene-expression/datasets" target="_blank">10x Genomics</a>
				<br/>
				Gene expressions in bone marrow mononuclear cells from a patient with acute myeloid leukemia (AML) and two healthy donors used as controls. The data includes over 8000 cells and 1000 genes with the highest dispersion. This is a data that comes with <a href="https://support.10xgenomics.com/single-cell-gene-expression/software/visualization/latest/what-is-loupe-cell-browser" target="_blank">Loupe Cell Browser</a>, and includes cells from three separate experiments with data sets published on 10x Genomics single-cell data sets page: AML027 Pre-transplant BMMCs, Frozen BMMCs (Healthy Control 1), and Frozen BMMCs (Healthy Control 2).
			</td>
		</tr>
		<tr>
			<td>2</td>
			<td>PBMC3k-processed</td>
			<td>Zheng, G. X., Terry, J. M., ... Gregory, M. T. (2017). <a href="https://www.nature.com/articles/ncomms14049" target="_blank">Massively parallel digital transcriptional profiling of single cells</a>. Nature communications, 8, 14049.</td>
			<td><a href="https://github.com/kalyaniuniversity/scRNA-seq-datasets/tree/master/PBMC3k/datasets" target="_blank">PBMC3k-processed</a></td>
			<td><a href="https://scanpy.readthedocs.io/en/stable/api/scanpy.datasets.pbmc3k_processed.html" target="_blank">scanpy.datasets.pbmc3k_processed</a></td>
			<td>
				The data consist in 3k PBMCs from a Healthy Donor and are freely available from <a href="https://support.10xgenomics.com/single-cell-gene-expression/datasets/1.1.0/pbmc3k" target="_blank">10x Genomics</a>.
			</td>
		</tr>
	</tbody>
</table>