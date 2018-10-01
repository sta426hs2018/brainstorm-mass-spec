# Mass-spectrometry

This repository was created by members of group 4:
* Ricards Marcinkevics
* Pablo Vargas
* Claude Renaux
* Samriddhi Buxy
* Emanuel Sonder

## Mode of Operation
Four main steps:
1. Sample Preparation  
2. Ionization  
3. Separation  
4. Detection  

<br><br>

1. **Sample preparation:** Usually sample have to be prepared for the analysis by mass spectrometry. Depending on the molecules/samples different procedures do exist. In proteomics, the samples are typically treated by adding denaturating aggents and proteases to diggest the proteins into (charged) peptides. Samples are usually injected via a column to obtain a separation in time of the peptide population.

2. **Ionization:** In order to be able to measure molecules by mass spectrometry they need to be charged. Different operation modes for ionizing (and fragmenting) do exist such as electron spray ionization (ESI), Matrix Assisted Laser Desorption Ionisation (MALDI) etc.

3. **Separation:** The mass analyzers make use of the charge of molecules. Common techniques are Time-of-flight (TOF), Quadrupole Mass Filters and Ion Traps. Time-of-flight (TOF) is arguably the most basic seperation technique and uses an electrical field in which the charged fragments are accelareted. The time molecules need to cover the distance in the analyzer depends upon the mass of the molecule (assuming equal charge).

4. **Detection:** Detectors are either based on induction or impact. When based on impact, the ion hits the surface and generates electrons, which are then turned into signal, in contrast induction relies upon the current induced of ion passing by the detector.
Sequentially, the mass over charge ratio pattern is recorded.

## Data representation and analysis
Data is produced by mass spectrometer. A broad range of mass spectrometers are used, that in turn produces various types of data. Data is most commonly represented in form of mass spectrum (intensity vs. mass-to-charge ratio plot), which is best represented by a chromatogram.

Other types of mass spectrometry data are well represented as a three-dimensional contour map. In this form, the mass-to-charge ration is on the x-axis, intensity the y-axis, and an additional experimental parameter, such as time, is recorded on the z-axis.

Analysis of mass spectra can be done by a computer algorithm called formula generator that calculates all molecular formulas that theoretically fit a given mass with specified tolerance. A recent technique for structure elucidation in mass spectrometry is precursor ion fingerprinting.

## Applications
Applications of mass-spectrometry include [(see this page for more applications)](https://www.thermofisher.com/ch/en/home/industrial/mass-spectrometry/mass-spectrometry-learning-center/mass-spectrometry-applications-area):
* characterization of proteins;
* cancer screening, biomarker discovery and profiling;
* drug discovery, metabolism studies, drug therapy monitoring;
* arson investigation, drug abuse confirmation, unknown compound identification.


## Resources

### Useful Links
* [What is mass spectrometry?]( https://www.thermofisher.com/ch/en/home/industrial/mass-spectrometry/mass-spectrometry-learning-center.html) Short and basic explanation of Thermo Fisher who produces the machines.
* [Mass Spectrometry Technology Overview](https://www.thermofisher.com/ch/en/home/industrial/mass-spectrometry/mass-spectrometry-learning-center/mass-spectrometry-technology-overview.html) More details about the technology used in mass spectrometry.
* [Wikipedia article about mass spectrometry](https://en.wikipedia.org/wiki/Mass_spectrometry#Data_and_analysis)

* [Slides](http://dia-swath-course.ethz.ch/downloads.html) and [videos](http://dia-swath-course.ethz.ch/videos.html) about proteomics organized by the group under Prof. Aebersold at ETH.


### Figures
![Workflow of Mass Spectrometry for metabolomics research](https://github.com/sta426hs2018/brainstorm-mass-spec/blob/master/metabolomics-fig.jpg)
Figure 1. Workflow for targeted (A) and untargeted (B, C) metabolomics. From Baig, Pechlaner & Mayr (2016). Caveats of Untargeted Metabolomics for Biomarker Discovery. 

![Workflow of Mass Spectrometry for proteomics research](https://github.com/sta426hs2018/brainstorm-mass-spec/blob/master/proteomics-fig.jpg)

Figure 2. Workflow for shotgun proteomics. From Choudhary & Mann (2010). Decoding signalling networks by mass spectrometry-based proteomics.

