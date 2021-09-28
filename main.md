# Building together the future of glacier modelling - what will be glacier modelling in 5 years or more !

The aim of this work is to think, discuss, exchange together about global modelling of mountain glaciers (that could be applied to the framework of OGGM) in a calloborative way, thinking to short- and long-term modeling evolution, and by taking time! The results should serve us to provide ideas to our projects, code developments, students work and maybe more largely to other researchers. It also aims to advertise about the synergies between glacier models, and also the limitations. 

## Introduction

**OGGM (Open Global Glacier Model) is an open source modelling framework for glaciers**

The model accounts for glacier geometry (including contributory branches) and includes an explicit ice dynamics module and a calving parametrization. It can simulate past and future mass-balance, volume and geometry of (almost) any glacier in the world in a fully automated and extensible workflow. We rely exclusively on publicly available data for calibration and validation. OGGM is modular and supports novel modelling workflows: it loves to be remixed and reused! (see **https://oggm.org/** for more information about the model and code, and **https://gmd.copernicus.org/articles/12/909/2019/** for more information about the physic).

## 1. What is a glacier model (like OGGM) able to do today (which is not ongoing work) ?

- Doing future long-term simulation, e.g. superior to 200-300 years
- Performing climate variability simulations, e.g. looking to seasonal mass balances evolution or ENSO influence on global glacier mass variations
- Coupling global hydrological model with runoff calculated by OGGM
- Document how to contribute in the core oggm code with examples at different levels and for different part of the modelling framework
g

## 2. Which studies can be performed by code development of a glacier model (OGGM for example, adding which code development is needed) ?

- Global debris-covered simulations (global test and calibration of the development of the debris-covered parametrisation)
- Influence of ocean water warming to frontal ablation for tidewater glaciers (adding a temperature dependency to the frontal ablation)
- Modeling rock glaciers (new surface mass-balance module and new rheology)
- Global evolution of proglacial lakes (parametrisation of bedrock evolution after glacier retreat)
- 

## 3. Which studies could be possible to conduct with technological/theoritical break development (which technological/theoritical) ?

- Global coupling between the downscaling GCM-RCM and OGGM (computational ressources -> quantum computer)
- Large-scale Mars ice sheet simulation (material which is not only ice, more observation about the glacier geometry and mass balance, maybe OGGM in 3D)
- Surface velocity / surface mass balance / glacier outline data assimilation to reconstruct past global glacier variations (computational ressources and data)
- Finer spatial resolution (more precise DEM and maybe computational ressources)
- Hydrology influence on glacier dynamic (other sliding law and/or data to calibrate sliding)
- Monte-Carlo approach for global glacier simulations and derive uncertainties (defining the framework of the approach, maybe computational ressources)
- 

## 4. Where to go with a glacier model ?

- Which model complexity do we need ? For which goal ? Are more complex models the enemy of more precise simulations ?
- What is the most suitable: a large and flexible community framework including lot of different SMB/ice dynamic modules or a large diversity of models ?
- Is it a long-term perspective to couple OGGM SMB and 3D full-stokes ice dynamic ?
- Do we need 2D, 3D into OGGM ?
- Do we need surface energy budget into OGGM ?
- 

## 5. Which essential scientific questions can not be replied with a glacier model (like OGGM model) ?

- Long-term past reconstruction (glacial and inter-glacial eras)
- Individual glacier simulations
- Non linearities SMB-related processes depending on the OGGM future choices and philosophy ...

## 6. OGGM braimstorming

- Best use of data (global dataset, mass balance, surface velocity ...) to calibrate OGGM to avoid spatial extrapolation and to validate the model - lot of challenges will come with these new dataset
- Communication -> continuum between observation (in situ and remote sensing) and modelling; different solutions for different glaciers, different studies ...
- Uncertainty evaluation, sort of ensemble simulation inside the glacier model (Bayesian approach); reduce the range of the ensemble by adding a new process; which statistical framework to test, calibrate and validate the range of the ensemble; uncertainties could be larger than what we expect
- Keep in mind when building research ideas to work all together in terms of different communities
- Workshops: which do we invite ? which topics have to be presentend / discussed ? exchange between scientific research
- Next big steps: uncertainties, close range projections, future projection communication, smaller scales, think the work we do as scientific questions not for policymakers or sea-level science, importance of natural variability, using oggm for the past (attribution/validation) ...
- Test cases for OGGM at individual glacier levels: high spatio-temporal resolution, lot of in situ data, understand what is not well represented into oggm compared to fine models, ...
- Work in one glacier is not a solved problem ! and very hard for all models, not only oggm
- Using hydrological model to compute sea-level contribution from glaciers
- Is it still valid in 10 years to continue to model a glacier as a flowline model ? Distributed mass-balance model -> difficult problem about the ice mass over high elevation mountains
- GPU for computation efficiency
- OGGM is really a framework ! OGGM has to be ready for spatial mass balance (full stokes emulation fast enough for global application)
- Running tidewater glaciers for transient simulation in the past
- Glacier temperature sensitivity not constant over the time
- Non existing glaciers into the inventory at the period of simulation
- What oggm would like to have from wgms: global and temporal evolution of mass-balance, wgms being more accessible database (metadata), having several inventories in time (lookup table to check the data), 
- How much oggm will be slower with uncertainty framework ? Making OGGM faster
- Data assimilation framework for oggm
- Commun grants (observation and modelling): code development, dataset mangagement ...
- How the OGGM community is growing with advantages and disavantages ? Very oppen to speak open in slack about plans, ideas ... because we are bigger than in the past, so maybe new comers are afraid to ask all the questions they have - we are not in computation in the community - not doing the work twice - putting the projects into the website for example with more details on the projects - slack channel for beginners 
- For the next decade, combining oceanography, atmosphere, glacier modelling, hydrology ... (that's a dream ;-) 
- Fear to add noise into OGGM slack: not a problem but good way to ask a question with a little scientific background (same for programming) - if the question is well prepared, be very welcome to ask everything - fear that the model is big, the community is big !
- Automatic calibration when you use your own dataset
- Protection of the code: rename of function for example -> warnings ...
- PROJECT PLANS:
  - better understand uncertainties and linearity assumption + seasonal / decadal forecast (Innsbruck project)
  - roe's approach in a global scale (detection/attribution - Brêmen project)
  - regional differences of glacier contribution to SLR, focus on climate downscalling and calibration/validation (Grenoble PhD thesis project)
  - lake-terminating glaciers in HMA (Utrecht project)
  - glacier modelling with complex model and data assimilation (Erlangen project)

## Conclusion

**All ideas are welcome !** And their feasibility, philosophy, scientific and/or societal interests, if the suggested developments will improve our results, our knowledges, ... can be discussed during the workshop and beyond. Feel very free to participate !

**Suggestion - building together a word cloud about what OGGM represents ?** For that, please write 3 to 5 words in the following link (please take care of the orthograph, use the British English spelling and uppercase the first letter): **https://answergarden.ch/2071148**

**Authors** (please add your name here):
##### Champollion Nicolas<sup>1</sup>, ...
#####

**Affiliations** (please add your affiliation here):
##### <sup>1</sup> Institut des Géosciences de l'Environnement, UGA / CNRS / IRD / Grenoble-INP
##### <sup>2</sup>
