
# Class: controlled term value


A controlled term or class from an ontology

URI: [nmdc:ControlledTermValue](https://microbiomedata/meta/ControlledTermValue)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[OntologyClass],[OntologyClass]<term%200..1-++[ControlledTermValue&#124;has_raw_value(i):string%20%3F;type(i):string%20%3F],[Biosample]++-%20env_broad_scale%201..1>[ControlledTermValue],[Biosample]++-%20env_local_scale%201..1>[ControlledTermValue],[Biosample]++-%20env_medium%201..1>[ControlledTermValue],[Biosample]++-%20chem_administration%200..1>[ControlledTermValue],[Biosample]++-%20env_broad_scale(i)%200..1>[ControlledTermValue],[Biosample]++-%20env_local_scale(i)%200..1>[ControlledTermValue],[Biosample]++-%20env_medium(i)%200..1>[ControlledTermValue],[OmicsProcessing]++-%20omics%20type%200..1>[ControlledTermValue],[Biosample]++-%20samp_mat_process%200..1>[ControlledTermValue],[AttributeValue]^-[ControlledTermValue],[OmicsProcessing],[Biosample],[AttributeValue],[Activity])](https://yuml.me/diagram/nofunky;dir:TB/class/[OntologyClass],[OntologyClass]<term%200..1-++[ControlledTermValue&#124;has_raw_value(i):string%20%3F;type(i):string%20%3F],[Biosample]++-%20env_broad_scale%201..1>[ControlledTermValue],[Biosample]++-%20env_local_scale%201..1>[ControlledTermValue],[Biosample]++-%20env_medium%201..1>[ControlledTermValue],[Biosample]++-%20chem_administration%200..1>[ControlledTermValue],[Biosample]++-%20env_broad_scale(i)%200..1>[ControlledTermValue],[Biosample]++-%20env_local_scale(i)%200..1>[ControlledTermValue],[Biosample]++-%20env_medium(i)%200..1>[ControlledTermValue],[OmicsProcessing]++-%20omics%20type%200..1>[ControlledTermValue],[Biosample]++-%20samp_mat_process%200..1>[ControlledTermValue],[AttributeValue]^-[ControlledTermValue],[OmicsProcessing],[Biosample],[AttributeValue],[Activity])

## Parents

 *  is_a: [AttributeValue](AttributeValue.md) - The value for any value of a attribute for a sample. This object can hold both the un-normalized atomic value and the structured value

## Referenced by Class

 *  **[Biosample](Biosample.md)** *[biosample➞env_broad_scale](biosample_env_broad_scale.md)*  <sub>1..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **[Biosample](Biosample.md)** *[biosample➞env_local_scale](biosample_env_local_scale.md)*  <sub>1..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **[Biosample](Biosample.md)** *[biosample➞env_medium](biosample_env_medium.md)*  <sub>1..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[chem_administration](chem_administration.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[env_broad_scale](env_broad_scale.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[env_local_scale](env_local_scale.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[env_medium](env_medium.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[experimental_factor](experimental_factor.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[growth_facil](growth_facil.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[host_body_product](host_body_product.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[host_body_site](host_body_site.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[host_disease_stat](host_disease_stat.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[host_phenotype](host_phenotype.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[omics type](omics_type.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[plant_growth_med](plant_growth_med.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[plant_struc](plant_struc.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[ploidy](ploidy.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**
 *  **None** *[samp_mat_process](samp_mat_process.md)*  <sub>0..1</sub>  **[ControlledTermValue](ControlledTermValue.md)**

## Attributes


### Own

 * [term](term.md)  <sub>0..1</sub>
     * Description: pointer to an ontology class
     * Range: [OntologyClass](OntologyClass.md)

### Inherited from attribute value:

 * [has raw value](has_raw_value.md)  <sub>0..1</sub>
     * Description: The value that was specified for an annotation in raw form, i.e. a string. E.g. "2 cm" or "2-4 cm"
     * Range: [String](types/String.md)
 * [was generated by](was_generated_by.md)  <sub>0..1</sub>
     * Range: [Activity](Activity.md)
 * [attribute value➞type](attribute_value_type.md)  <sub>0..1</sub>
     * Description: An optional string that specified the type of object.
     * Range: [String](types/String.md)
     * Example: nmdc:Biosample None
     * Example: nmdc:Study None