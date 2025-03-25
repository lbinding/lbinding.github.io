# Portfolio

<p> While the ongoing work includes sections about my current research, which might not be available, this represents work with publicly available code, even if it is not completely finished.  </p>

## Anatomically Targeted Automated Tractography
<p> I developed software aimed at efficiently and automatically reconstructing connections between brain regions. This tool utilised normative mapping to compare diffusion data from healthy controls with that of epilepsy patients, enabling the subdivision of tracts into their respective sub-fascicles. Our findings showed that it reduced the need for manual intervention to under 3%, compared to the next best method, which required manual input in over 60% of cases. This is now regularly implemented in surgical navigation software to avoid critical white matter structures. Ongoing efforts are focused on expanding this normative database to include data from hundreds of healthy controls. </p>

[Initial Release](https://github.com/lbinding/AT-AT)

## TemporalSlice 
<p> One difficult and time-consuming aspect of postoperative research is delineating resected tissue on a post-operative scan. TemporalSlice was developed to enhance this process using synthetically generated data, as manually created data can be inaccurate. This code includes all the steps needed to generate synthetic data from a few ground-truth, non-resected brain scans. The most up-to-date version is designed to be agnostic to MRI acquisition parameters and data quality. While I am working to ensure compatibility across different types of acquisitions, I have uploaded a model that currently works with T1 images. I have found this approach to be more accurate than manually delineated resection cavities and the paper is currently in progress.  </p>

[Initial Release](https://github.com/lbinding/TemporalSlice/tree/master)

## White matter fibre bundles and memory 
<p>In this project, we explored the relationship between white matter fibre bundles and both immediate and delayed postoperative verbal memory. Drawing on our findings and existing literature, we propose a direct memory route mediated by the Fornix, alongside an indirect route facilitated by the Ventral Cingulum. This project is currently under review at *Brain*.</p>

[View Github](https://github.com/lbinding/MemoryPaper)
