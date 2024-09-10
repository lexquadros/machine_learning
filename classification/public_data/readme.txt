Objectives

The study aims to create a predictive classification of revenue capacity using public socioeconomic data. It is an approximation of the socioeconomic reality and is limited to the selected time period. Various sources of information were aggregated, requiring extensive pre-processing time. At the end of the pre-processing, I chose to use 5% of the original dataset due to computational processing constraints. This way, I extracted a representative sample of all classes.


Public datasets

The use of public data for predictive models in machine learning has become an increasingly common and accessible practice, thanks to the growing availability of high-quality datasets provided by governments, research institutions, and international organizations. These data cover a wide range of areas, such as health, economics, environment, education, and transportation, offering valuable opportunities for the creation of models that can predict trends, identify patterns, and make informed decisions.

In this case I used governamental datesets available in https://sisu.mec.gov.br/, https:ibge.gov.br e https://www.salario.com.br/tabela-salarial/. More details in the notebook.

The Ethical Approach:
- The data was depersonalized during pre-processing to preserve the anonymity of individuals;
- Although public, the data is not easily accessible through apparent links on the Ministério da Educação’s portal; however, it is available through a provided link.

Data Handling:
- The data was processed in a different notebook (lexquadros/machine_learning/pre_processing_EDA);
- At times, the data was manipulated in separate notebooks to avoid cluttering the construction of a predictive machine, such as in the case of Cluster Analysis, which is located in lexquadros/machine_learning/cluster/Kmeans_Kmodes_Kprototypes.

