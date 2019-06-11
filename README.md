# GSQ Dataset Profile
This is a model of a general `permit`.

<img src="model/dataset.svg" style="width:800px;" alt="Permit model" />  

**Fig. 1**: The general model of a permit.  

It is a profile of the a permit. It is used for describing the [Geological Survey of Queensland (GSQ)](https://www.business.qld.gov.au/industries/mining-energy-water/resources)'s permits.


## Usage
A `permit` is the authority to perform a mining activitiy on a piece of land.

<img src="model/level0-conceptual-model.svg" style="width:800px;" alt="Level 0 conceptual model" />  

**Fig. 2**: The level 0 conceptual model of a permit.

#### An example:
* Example here.


## Profile Resources
This profile is presented as a series of files that perform different roles:

* [Guidance document](Guidance.pdf) - a written document explaining how to use this profile
* [model](model/) - the *model* folder contains this profile's models in both graphical (SVG) and machine-readable, textual, form ( [RDF](https://www.w3.org/RDF/) turtle).
* [imports/](imports/) - other ontologies this profile imports.
* [constraints.ttl](constraints.ttl) - a constraints file, formulated using [SHACL](https://www.w3.org/TR/shacl/), that can be used to validate instances of metadata to check conformance with this profile.
* [profile.ttl](profile.ttl) - the profile declaration. A description of all of the items in this profile (the formal model, validating resources, documentation etc.) according to the W3C's [Profiles Ontology](https://www.w3.org/TR/dx-prof/) which describes how all the parts related to one another, the roles they play (to give *guidance* for use, to *validate* data etc.) and how this profile *profiles* the various standards listed above.


## GSQ classes
CLasses used in this profile:
1. [TBA](https://github.com/geological-survey-of-queensland/)


## OWL classes
1. [dcat:Dataset](https://w3c.github.io/dxwg/dcat/#Class:Dataset)
2. [dcat:Theme](https://w3c.github.io/dxwg/dcat/#Property:resource_theme) - used to categorise the resource, the GSQ themes are described as [skos:Concept](http://www.w3.org/2004/02/skos/core#Concept)s in the vocabulary [GSQ Data Themes](http://vocabs.gsq.digital/vocabulary/gsq-data-themes)
3. [dcat:Distribution](https://w3c.github.io/dxwg/dcat/#Class:Distribution)
4. [dct:Location](https://w3c.github.io/dxwg/dcat/#Class:Location)
5. [dct:creator](https://w3c.github.io/dxwg/dcat/#Property:resource_creator)
6. [dct:publisher](https://w3c.github.io/dxwg/dcat/#Property:resource_publisher)
7. [dct:contactPoint](https://w3c.github.io/dxwg/dcat/#Property:resource_contact_point)
8. [dct:title](https://w3c.github.io/dxwg/dcat/#Property:resource_title)
9. [dct:description](https://w3c.github.io/dxwg/dcat/#Property:resource_description)
10. [dct:identifier](https://w3c.github.io/dxwg/dcat/#Property:resource_identifier)
11. [dct:license](https://w3c.github.io/dxwg/dcat/#Property:resource_license) - not shown in diagram for readability


## Vocabularies
The vocabularies used in this profile are:
1. [Queensland Mining Permit](https://vocabs.gsq.digital/vocabulary/qld-mining-permit)


## License
The content of this repository is licensed for use with the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) for details.


## Contacts 
*owner*:  
**Mark Gordon**  
*Director - Geoscience Information*  
Geological Survey of Queensland  
<mark.gordon@dnrme.qld.gov.au>  

*author*:  
**David Crosswell**  
*Project Director*  
Geological Survey of Queensland  
<david.crosswell@dnrme.qld.gov.au> 
