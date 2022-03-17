## MDMC-NEP top-level ontology

This repository collects the ongoing work towards the development of the top-level ontology based on common terms defined for the Joint Lab 
"Integrated Model and Data Driven Materials Characterization" (MDMC) and for the "Nanoscience Foundries and Fine Analysis Europe Pilot" (NEP).
The top-level glossary defining the terms is available (as a living document which can be constantly updated) on the NEP website: https://www.nffa.eu/apply/data-policy/glossary

## Aim

This ontology of top-level terms aims at describing the entire experimental workflow, from the sample preparation to the scientific publication, representing the high-level provenance information. 
The ontology is planned to be initially adopted in MDMC and NEP. 
In future, it might also be adopted by other Materials Science projects. 
This will have the huge advantage of having a **common** description of concepts and relationships in the domain of Materials Science. 
This will offer a set of metadata which, in turn, will increase the interoperability and the reuse of the produced data.

## Ontology development

Our ontology reuses the W3C Provenance Ontology (PROV-O): https://www.w3.org/TR/prov-o/

Three classes provide a basis for the PROV-O: 
- **Entity** is a physical, digital, conceptual thing with some fixed aspects.
- **Activity** is something that occurs over period of time and acts with entities.
- **Agent** is something that bears some responsibility for an activity taking place.

The genus-differentia is used to unpack the definition of terms, reusing the three PROV-O classes as genus:
- Genus is the existing concept on which the new concept is based.
- Differentia is the difference(s) about the new concept.

## Future extensions

The top-level ontology is planned to be extended thanks to the adoption of fine-grained ontologies already existing, 
e.g. the Material Science Lab Equipment (MSLE) Ontology. 

## Planned Applications

* Scanning Tunneling Microscopy (STM) images 
* Scanning Electron Microscopy (SEM) images
* Transmission Electron Microscopy (TEM) images

## The Team

This activity is a sub-task of the MDMC Metadata Working Group. Thus, the team is a sub-group of the MDMC Metadata Working Group. Additional participants are included to enforce the collaboration on specific use cases. 

- **Rossella Aversa** (Steinbuch Centre for Computing, Karlsruhe Institute of Technology): task leader, designs the idea and plans the activities
- **Ahmad Z. Ihsan** (Forschungszentrum Jülich, Institute of Advanced Simulations – Materials Data Science and Informatics (IAS-9), RWTH Aachen University, Faculty 5): main developer, implements the OWL file
- **Mehrdad Jalali** (Institute of Functional Interfaces, Karlsruhe Institute of Technology): developer, implements the MSLE Ontology
- **Mirco Panighel** (Consiglio Nazionale delle Ricerche - Istituto Officina dei Materiali): developer, contributes to the STM application 
- **Elda Osmenaj** (Consiglio Nazionale delle Ricerche - Istituto Officina dei Materiali): developer, contributes to the STM application

## History

- 08.09.2021 Rossella presented the activities to the MDMC Working Group. Ahmad and Mehrdad agreed to establish the sub-task
- 16.09.2021 Rossella, Ahmad and Mehrdad started regular weekely meetings
- 28.09.2021 Ahmad created the repository on his personal GitHub page, including the first version of OWL
- 05.06.2021 Mehrdad presented the first graphical version to the MDMC Working Group
- 06.10.2021 Rossella and Ahmad presented the first version of competency questions
- 26.10.2021 Mehrdad presented the second graphical version to the MDMC Working Group
- 27.10.2021 Mehrdad presented the MSLE Ontology mapping example to the MDMC Working Group, Rossella presented the second version of competency questions
- 10.11.2021 Rossella, Ahmad and Mehrdad agreed on presenting the ontology in a paper with an application. Looking for applications
- 18.01.2022 Elda and Mirco joined the group, presenting their use case on STM
- 14.02.2022 Rossella and Ahmad presented the results at the MDMC Workshop
- 18.02.2022 Rossella forked the repository to the KIT GitHub page
- 01.03.2022 Mehrdad graphically represented the Data Analysis Lifecycle according to commonly agreed definitions
- 08.03.2022 Rossella created a comprehensive list of competency questions. Rossella, Ahmad, Mehrdad and Elda discussed the mapping of the STM usecase

## Acknowledgements

* This work has been supported by the Joint Lab “Integrated Model and Data Driven Materials Characterization” (MDMC), the research programs “Engineering 
Digital Futures” and “Materials System Engineering” of the Helmholtz Association of German Research Centers and the Helmholtz Metadata Collaboration Platform.
* This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No. 101007417 within 
the framework of the NFFA-Europe Pilot (NEP) Joint Activities.

