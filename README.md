# Mass-Cytometry-Data-Analysis [1]
Data science tools for analysis mass cytometry by time of flight (CyToF)
Cytometry is measurement of cell characteristics.Features that can be measured by cytometric methods are cell morphology (shape/structure), cell count, DNA content, presence or obsence of a protein on a cell surgace or cell cytoplasm. 

For a Mass cytometry experiment, cells are stained with antibodies, and metal isotopes are employed as reporter groups. Staining panels of 35 or more antibodies are designed to quantify cell surface phenotypes, cell cycle state, apoptosis, metabolism, proliferation, and activation states of intracellular signaling pathways, as depicted in figure below:

![image](https://user-images.githubusercontent.com/10026216/137164031-819c2756-4b7c-4926-a822-cf074f11613f.png)
Figure is taken from [1].


CyTOF (Fluidigm), is a variation of flow cytometry in which antibodies are labeled with heavy metal ion tags rather than fluorochromes.  Readout is by time-of-flight mass spectrometry.  This allows for the combination of many more antibody specificities in a single samples, without significant spillover between channels.  

There are standardized panels for  immunophenotyping, phenotyping+intracellular cytokine staining (ICS), and phenotyping+phospho-CyTOF, each with 30 to 38  antibodies.   

Immunophenotyping:  A number of (30-50) antibody CyTOF immunophenotyping panel is designed for use with cryopreserved PBMC, though it could be adapted for other sample types.  A limited number of additional antibodies can be added to open channels, subject to availability.

Intracellular cytokines:  the (30-50) antibody CyTOF ICS panel is aimed primarily at dissection of T cell responses.  Limited substitutions are possible (with common ones as listed).

Phospho-CyTOF:  the (30-50) antibody phospho-CyTOF panel can be used with the indicated stimuli to read out a broad array of signaling pathways in many different cell subsets.  Additions or substitutions in this panel are more difficult, due to the requirement for surface marker antibodies to work well on fixed epitopes.

There is a list of standard antibodies in these three CyTOF panels here. 

Fluidigm Corporation is currently the only vendor of mass cytometry instruments with their CyTOF systems. The first CyTOF was released in 2009, followed by the CyTOF2® in 2013, and most recently the Helios™ in 2015. 
![image](https://user-images.githubusercontent.com/10026216/137162678-bf8cedb2-aa76-484b-9d42-9970e7a3a264.png)

References:
[1] -Di Palma, S. and Bodenmiller, B., 2015. Unraveling cell populations in tumors by single-cell mass cytometry. Current opinion in biotechnology, 31, pp.122-129.
[2] - Olsen, L. R., Leipold, M. D., Pedersen, C. B., & Maecker, H. T. (2019). The anatomy of single cell mass cytometry data. Cytometry Part A, 95(2), 156-172.
