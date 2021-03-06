# Atyimo - Record Linkage Application for Heterogeneous Platforms

# Description
AtyImo implements a mixture of deterministic and probabilistic routines for data linkage. initially developed in 2013 to serve as a linkage tool supporting a joint Brazil–U.K. project aiming at building a large population-based cohort with data from more than 100 million participants and producing disease-specific data to facilitate diverse epidemiological research studies.

# Requirements: 
Java 8+, Spark 2.1.x, gcc

# Setup steps:
1. Edit the config.py file
2. edit the line "export PATH=$PATH:/path/to/spark/bin" using the location of Apache Spark's installation
3. Use the 'run_all.sh' script to execute the atyimo. 


Authors
==============
Robespierre Pita and Clicia Pinto and Marcos Barreto and Spiros Denaxas
1. FEDERAL UNIVERSITY OF BAHIA (UFBA), ATYIMOLAB (www.atyimolab.ufba.br)
2. University College London, Denaxas Lab (www.denaxaslab.org)

More information
=================
* PITA, Robespierre et al. [On the accuracy and scalability of probabilistic data linkage over the Brazilian 114 million cohort](https://ieeexplore.ieee.org/document/8293793). IEEE journal of biomedical and health informatics, v. 22, n. 2, p. 346-353, 2018.

* Pita R., Mendonça E., Reis S., Barreto M., Denaxas S. (2017) [A Machine Learning Trainable Model to Assess the Accuracy of Probabilistic Record Linkage.](https://link.springer.com/chapter/10.1007/978-3-319-64283-3_16) In: Bellatreche L., Chakravarthy S. (eds) Big Data Analytics and Knowledge Discovery. DaWaK 2017. Lecture Notes in Computer Science, vol 10440. Springer.

* PITA, Robespierre; PINTO, Clicia; MELO, Pedro; Silva, Malu; BARRETO, Marcos; RASELLA, Davide. (2015) [A Spark-based workflow for probabilistic record linkage of healthcare data. Workshop on Algorithms and Systems for MapReduce and Beyond](http://ceur-ws.org/Vol-1330/EDBTICDT-WS2015-complete.pdf) (BeyondMR - EDBT/ICDT 2015), Brussels.


* PINTO, Clicia; PITA, Robespierre; BARBOSA, George; ARAÚJO, Bruno; BERTOLDO, Juracy; SENA, Samila; REIS, Sandra; FIACCONE, Rosemeire; AMORIM, Leila; ICHIHARA, Maria Yuri; BARRETO, Mauricio; BARRETO, Marcos; DENAXAS, Spiros. [Probabilistic integration of large Brazilian socioeconomic and clinical databases.](http://dx.doi.org/10.1109/CBMS.2017.64) 30th IEEE International Symposium on Computer-Based Medical Systems (CBMS 2017), Thessaloniki, 2017. 

* PINTO, Clicia; BORATTO, Murilo; ALONSO, Pedro; BARRETO, Marcos. Scaling probabilistic record linkage on multicore and multi-GPU system. 17th International Conference on Computational and Mathematical Methods in Science and Engineering (CMMSE 2017), Cadiz, 2017
