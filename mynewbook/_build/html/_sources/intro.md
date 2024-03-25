# Leveraging Cloud-based OpenAI's LLMs to Create Learning-as-a-Service (LaaS) Solutions for Culturally Rich Conversational AI: A Study Using the Legacy of Slavery Dataset

### This Project uses Maryland State Archives' Legacy of Slavery Dataset Collection - Domestic Traffic Ads as a Case Study
* **Author:** Rajesh Kumar GNANASEKARAN
* **Reviewer:** Richard MARCIANO
* **Community Members:** Christopher HALEY (Maryland State Archives)
* **Source Available:** https://github.com/cases-umd/Legacy-of-Slavery
* **License:** [Creative Commons - Attribute 4.0 Intl](https://creativecommons.org/licenses/by/4.0/)
* **Prior Publications:** 1. R. K. Gnanasekaran, R. Marciano, "Piloting Data Science Learning Platforms through the Development of Cloud-based interactive Digital Computational Notebooks," 2021 ISGC. 2. L. A. Perine, R. K. Gnanasekaran, P. Nicholas, A. Hill and R. Marciano, "Computational Treatments to Recover Erased Heritage: A Legacy of Slavery Case Study (CT-LoS)," 2020 IEEE International Conference on Big Data (Big Data), Atlanta, GA, USA, 2020, pp. 1894-1903, doi: 10.1109/BigData50022.2020.9378110. 3. P. Nicholas, R.K. Gnanasekaran, L. Perine, A. Hill, R. Marciano. (2020). Establishing a Research Agenda for Archival Science through Interdisciplinary Collaborations between Archivists and Technologists. 2020 SAA Research Forum (invited for submission and under consideration).


## Introduction

### Overall Objective
The overall objective of this project is to create multiple Learning-as-a-Service (LaaS) solutions to streamline and automate a large amount of repetitive work, consolidating information, and making it easier to access. LaaS can be used by almost any organization that has a degree of need for training or education at a variety of levels, especially at educational institutions. In this case, these solutions are designed to be cloud-hosted and are created specifically for easy on-the-go access by students, researchers of Undergraduate and Graduate majors in Digital Archives and Library Sciences. These solutions are primarily built to teach new topics and technologies as they relate to the field of Digital Archives and Library Sciences with focus on Computational Thinking Practices.

### Project Objective
To keep in line with the Overall objective, this project's specific objectives are:
*   To create unique LaaS solutions in the form of cloud-hosted, coherent and modularized digital notebooks that could be publicly accessed.
*   To teach interested individuals advanced computational thinking topics in a simple manner yet introducing them to the world-of-programming. This is achieved through the inherent capabilities of these unique digital notebooks that can be used to create plain-text instructions and explanations alongside with the computer programming code.
*   To use culturally rich dataset collections to use them in these case study LaaS solutions. This approach adds a third benefit to the project end users and the archivists as through these learning solutions, these collections that are not commonly accessed are made available for research and analysis by the budding students and researchers.

### The Legacy of Slavery Project at the Maryland State Archives (MSA)
This module is based on a case study involving [The "Legacy of Slavery Project"](http://slavery.msa.maryland.gov/) archival records from the Maryland State Archives. The Legacy of Slavery in Maryland is a major initiative of the Maryland State Archives. The program seeks to preserve and promote the vast universe of experiences that have shaped the lives of Maryland’s African American population. Over the last 18 years, some 420,000 individuals have been identified and data has been assembled into 16 major databases. The Maryland State Archives holds several essential types of records documenting freedom within its collections. One of the notable oneThe first are **Manumissions**, legal documents that frees an enslaved person from slavery on behalf of the slave holder. The second are **Certificates of Freedom**, documents that resulted from a 1805 General Assembly law that sought to identify Maryland’s free African American population and to control the availability of freedom papers. This legislation required those who were born free, or those who received their freedom from a slave owner, to record proof of their status in the county court. These documents, found in 111 record series at the Maryland State Archives arranged by the county of issuance, contain vital information about those who were enslaved. Everything from the names, age, physical description, location of the recipient’s birth and rearing, and names of the slave holder or witness who confirmed the person’s free status is usually included. These records have been uploaded and made available through the Legacy of Slavery searchable database. More information could be obtained from [here](http://slavery.msa.maryland.gov/html/news/recent-projects.html). The [AIC](https://ai-collaboratory.net/) has now partnered with the Maryland State Archives to help interpret this data and reveal hidden stories. This case study is performed on this dataset collection, referred to as the "Certificates of Freedom" (CoF) dataset.

### Certificates of Freedom in the State of Maryland
A Certificate of Freedom is a legal document that was issued to African Americans who were required to record proof of their freedom in the county court. The court would then issue them a Certificate of Freedom. If the person had been previously manumitted by an act of the slaveholder, the court clerk or register of wills would look up the manumitting document before issuing a certificate of freedom. 

#### 
One of the latest revelations which got public attention was the story of Smith Price, a founding member of the African Meeting House in Annapolis, which eventually became the First African Methodist Episcopal Church in 1803. According to Rebecca Morehouse [here](https://mdhistoricaltrust.wordpress.com/tag/smith-price/reburial), in 1980 excavations of certain burial remains were found which was later studied to be belonging to Mr. Smith Price, an enslaved later freed African American on whose land the Asbury United Methodist Church stands as of today. Several people, notably researcher Janice Hayes-Williams, worked hard to get approval for a reburial ceremony of Mr. Price's remains at St Anne's cemetery in Annapolis. A conjectural drawing of Smith Price by a forensic artist detective is shown here: 
![Smith Price Photo](Pics/smith_price_photo.jpg "Conjetural Drawing of Smith Price by Forensic Artist") 
[Source](https://mdhistoricaltrust.wordpress.com/tag/smith-price/reburial)

Upon analysis in the Certificates of Freedom dataset collection, we were able to find Smith Price's CoF as shown here: 

![Smith Price CoF](Pics/Smith_Price_CoF.png "Smith Price's Certificate of Freedom ")

By looking at the Smith Price's CoF, the conjectural drawing and the article published above gives us a chance to connect to the lives of enslaved people and several such stories and insights are still buried deep in the documents as dataset collections at the MSA. 

One other example is of an enslaved woman named "Lot Bell" who was identified in the CoF collection, and a forensic artist made a similar conjectural drawing of her as shown below: An article link [here](https://bayweekly.com/the-faces-of-freedom/) describes the project below led by Chris Haley at the Maryland State Archives.
![Lot Bell Photo](Pics/Lot-Bell_CoF.jpeg "Conjetural Drawing of Lot Bell by Forensic Artist")![Lot_Bell_CoF](Pics/Lot-Bell_portrait.jpeg "Lot Bell Certificate of Freedom")

These images tell us that the CoF dataset collection is a repository of rich cultural and human values which when seen through the contemporary scholar's lenses could unravel many more interesting and eyeopening insights as the ones above. 

### Computational Thinking Framework
This Project is organized in steps based on the Computational Thinking framework presented by [David Weintrop’s model of computation thinking](https://link.springer.com/content/pdf/10.1007%2Fs10956-015-9581-5.pdf)

![CT-STEM taxonomy](taxonomy.png "David W.'s CT Taxonomy")

Of these 4 major Practices, this Project applies 2 of them as indicated below:

![CT-STEM Taxonomy Practices Uses](Pics/taxonomy_used.png)

### **C**omputational Thinking Practices
#### Data Practices
 * Manipulating Data
 * Analyzing Data
 * Visualizing Data

#### All Computational Problem Solving Practices

## Learning Goals

### **A**rchival Practices
 * Digital Records and Access Systems

### **E**thics and Values Considerations
 * Contexualized Analysis of Data