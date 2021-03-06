# ILCDelphes
### Generic ILC detector model for Delphes  

New version of the ILC detector model is aviable for test. 
The main structure should is not expected to change. 
However, minor changes and improvements are still expected 
depending also on test results.

### Motivation

[Delphes](https://github.com/delphes/delphes) is a framework 
for fast simulation of a generic collider experiment. It allows to take
into account basic experimental effects as acceptance, efficiency 
and detector resolution, and provides also expected results of event 
reconstruction (as lepton identification, flavour taging and jet 
clustering). 

As a part of the [2021 Snowmass](https://snowmass21.org/start) study 
the new model has been developed for fast ILC detector simulation in Delphes. 
While it has been mainly based on the ILD detector concept, 
as presented in [ILD IDR](https://arxiv.org/abs/2003.01116),
it can be considered a generic ILC detector model, as expected performances
of both ILD and SiD are very similar and details of the detector design
are not taken into account in Delphes.

### Documentation 

More information on the implementation can be found in [**doc/**](doc/)

### Installation

No dedicated installation of the model is required. You just need to:

 1. Download the model repository, model files can be found in [**cards/**](cards/).
 2. Copy the main model file (`delphes_card_ILCgen.tcl`) 
and the include file catalog (`ILCgen/`) into `cards/` catalog 
of your Delphes installation.
 3. Run Delphes specifying `delphes_card_ILCgen.tcl` as the detector model.

### How to run it

Delphes support many input file formats, so it can be used to process
event samples generated with different event generators, 
including Whizard and Madgraph.
More information about Delphes installation and running can be 
found on [GitHub](https://github.com/delphes/delphes)

### Issues and contact

In case of problems, questions or requests, please:

- use Github [issue interface](https://github.com/ILCSoft/ILCDelphes/issues)
- or try to contact us directly by e-mail:
    - [Aleksander Filip Zarnecki](mailto:zarnecki@fuw.edu.pl)


