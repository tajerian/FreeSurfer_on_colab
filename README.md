# FreeSurfer on colab

$\color{red}{\text{FreeSurfer}}$ is a software package for the analysis and visualization of structural and functional neuroimaging data from cross-sectional or longitudinal studies. It is developed by the Laboratory for Computational Neuroimaging at the Athinoula A. Martinos Center for Biomedical Imaging. FreeSurfer is the structural MRI analysis software of choice for the Human Connectome Project.



![FreeSurfer](https://upload.wikimedia.org/wikipedia/commons/9/9e/Brainanim.gif "FreeSurfer")



FreeSurfer's $\color{red}{\text{recon-all}}$ command takes a long time to process an individual subject around $\color{red}{\text{6-24}}$ hours on a typical systenm, with some variation due to factors such as the quality of the input data.

For many researchers, this can be a prohibitively long time to wait, especially if the study contains dozens or hundreds of subjects.

***in this notebook I'll show you how to setup and run Freesurfer to overcome this issue***


