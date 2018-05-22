# Deduce: de-identification method for Dutch medical text

This project contains the code for DEDUCE: de-identification method for Dutch medical text as described in [Menger et al (2017)](http://www.sciencedirect.com/science/article/pii/S0736585316307365). De-identification of medical text is needed for using text data for analysis, to comply with legal requirements and to protect the privacy of patients. Our pattern matching based method removes Protected Health Information (PHI) in the following categories:

1. Person names, including initials
2. Geographical locations smaller than a country
3. Names of institutions that are related to patient treatment
4. Dates
5. Ages
6. Patient numbers
7. Telephone numbers
8. E-mail addresses and URLs

The details of the development and workings of the method, and its validation can be found in: 

[Menger, V.J., Scheepers, F., van Wijk, L.M., Spruit, M. (2017). DEDUCE: A pattern matching method for automatic de-identification of Dutch medical text, Telematics and Informatics, 2017, ISSN 0736-5853](http://www.sciencedirect.com/science/article/pii/S0736585316307365)

### Demo

An interactive demo of the code can be found [here](http://ads.science.uu.nl/deduce/)

### Prerequisites

* `nltk`
