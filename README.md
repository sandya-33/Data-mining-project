# Data-mining-project
CpSc 8650 (Section 1), Data Mining Course Project
Quality Evaluation of Skull Stripped Brain MRI Images
Background
Brain MRI imaging has been widely used by neurologists and neuroscientists in
disease diagnosis and human brain study since the 1980s. There are quite a few different
imaging modalities or sequences used in imaging the nervous system and producing
different kinds of brain MRI images, such as T1-weighted (T1W) images, T2-weighted
(T2W) images, Diffusion-weighted images (DWI), etc. To advance neuroimaging
research, more and more researchers share neuroimaging data in open access data
repositories for collaboration and knowledge dissemination. To ensure HIPAA
compliance, researchers often use skull-stripping tools to remove the image voxels that
represent the skull structure and facial features from the raw 3D MRI images before
sharing data. Skull stripping is a segmentation process to extract brain tissues from a raw
3D MRI image of a brain. This is one of the preliminary steps in neuroimaging research.
Various skull-stripping tools and algorithms have been proposed to extract brain images
(https://ieeexplore.ieee.org/document/7060986?reload=true&arnumber=7060986).
However, using these algorithms and tools for brain image segmentation is a tedious task
even for expert radiologists and the accuracy of results varies a lot from person to person.
Sometimes, the facial features are still in the processed images, and the other times, the
voxels representing actual brain tissues were removed. To ensure the quality of the skull
stripping process, researchers often spend a lot of time and effort to inspect the quality of
the segmentation results.
Project Requirements:
This project requires the students to develop a Data Mining algorithm or tool to check
the quality of the skull-stripped MRI images. This algorithm or tool must meet the
following two basic requirements:
1. Determine whether the facial features are removed to the extent that people
cannot identify the person based on the remaining facial features in the skull-
stripped MRI image.
2. Determine whether any brain voxels are unintentionally removed, resulting in the
loss of important brain information..
Students may further enhance their algorithms or tools with following possible directions
(not limited to):
1. Estimate the likelihood of the subject having residual facial features to be
recognized by people.
2. Design or find an algorithm that can reconstruct the skull-stripped image into an
image with facial features and determine how much this reconstructed image is
similar to the original MRI image.
3. Estimate the percentage of brain image voxels unintentionally removed by the
skull-stripping process..
