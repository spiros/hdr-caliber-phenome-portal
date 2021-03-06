---
layout: phenotype
title: Peptic ulcer disease
name: Peptic ulcer disease
phenotype_id: 4mSsuwVb7M6w3HhH94Jbov 
type: Disease or Syndrome
group: Digestive
data_sources: 
    - Clinical Practice Research Datalink GOLD
    - Hospital Episode Statistics APC for CPRD GOLD
clinical_terminologies: 
    - OPCS-4
    - Read Version 2
    - ICD-10
validation: 
    - cross-source
codelists: 
    - kuan_ulcer_peptic_4mSsuwVb7M6w3HhH94Jbov_Read2.csv
    - kuan_ulcer_peptic_4mSsuwVb7M6w3HhH94Jbov_ICD10.csv
    - kuan_ulcer_peptic_4mSsuwVb7M6w3HhH94Jbov_OPCS4.csv
valid_event_data_range: 01/01/1999 - 01/07/2016
sex: 
    - Female
    - Male
author: 
    - Kuan V
    - Denaxas S
    - Gonzalez-Izquierdo A
    - Direk K
    - Bhatti O
    - Husain S
    - Sutaria S
    - Hingorani M
    - Nitsch D
    - Parisinos C
    - Lumbers T
    - Mathur R
    - Sofat R
    - Casas JP
    - Wong I
    - Hemingway H
    - Hingorani A
publications: 
    - 'Kuan V., Denaxas S., Gonzalez-Izquierdo A. et al. A chronological map of 308 physical and mental health conditions from 4 million individuals in the National Health Service. The Lancet Digital Health - DOI: 10.1016/S2589-7500(19)30012-3' 
status: FINAL
date: 2019-05-20
modified_date: 2019-05-20
version: 1
---
### Primary care 
{% include csv.html csvdata=site.data.codelists.kuan_ulcer_peptic_4mSsuwVb7M6w3HhH94Jbov_Read2 %}
### Secondary care 
#### Diagnoses 
{% include csv.html csvdata=site.data.codelists.kuan_ulcer_peptic_4mSsuwVb7M6w3HhH94Jbov_ICD10 %}
#### Procedures 
{% include csv.html csvdata=site.data.codelists.kuan_ulcer_peptic_4mSsuwVb7M6w3HhH94Jbov_OPCS4 %}
### Implementation 
<pre>At the specified date, a patient is defined as having had 'Peptic ulcer disease' disease IF they meet the criteria for any of the following on or before the specified date. The earliest date on which the individual meets any of the following criteria on or before the specified date is defined as the first event date:

Primary care
1. 'Peptic ulcer disease' disease diagnosis or history of diagnosis or procedure during a consultation 
OR
Secondary care
1. ALL diagnoses of 'Peptic ulcer disease' disease or history of diagnosis during a hospitalization
OR
Secondary care (OPCS4)
1. ALL procedures for 'Peptic ulcer disease' disease during a hospitalization</pre> 
 
### Publications 
Kuan V., Denaxas S., Gonzalez-Izquierdo A. et al. _A chronological map of 308 physical and mental health conditions from 4 million individuals in the National Health Service_. The Lancet Digital Health - DOI <a href='https://www.thelancet.com/journals/landig/article/PIIS2589-7500(19)30012-3/fulltext'>10.1016/S2589-7500(19)30012-3</a>