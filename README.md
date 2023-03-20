# Gene-expression-AD-project
## Project Description
The dataset contains the expression levels of `77 proteins` or protein modifications in the `nuclear fraction of cortex in 72 mice.` There are 38 control mice and 34 trisomic mice (Down syndrome). Each mouse was subjected to 15 measurements per protein. The data contains a total of 1080 measurements per protein, and each measurement was treated as an independent sample/mouse. The eight classes of mice are categorized based on genotype, behavior, and treatment.

![alt text](https://github.com/yasmina-99/Gene-expression-AD-project/blob/main/download-10.png)


## Aim of the project
The primary aim of this project is to identify protein subsets that can discriminate between each class. The study was conducted by replicating the research idea proposed by Clara Higuera, Katheleen J. Gardiner, and Krzysztof J. Cios. The project's secondary goal is to practice statistical analyses and test for significant differences.

## Understading Alzheimer's Disease
Alzheimer's disease is a progressive brain disorder that affects memory, thinking, and behavior. It is the most common cause of dementia among older adults, and there is currently no cure. While the exact cause of Alzheimer's is not yet fully understood, it is thought to involve a complex interplay between genetic, environmental, and lifestyle factors.

People with Down syndrome are at increased risk of developing Alzheimer's disease as they age. This is because the extra copy of chromosome 21 that causes Down syndrome also carries the gene for amyloid precursor protein (APP), which is involved in the formation of beta-amyloid plaques in the brain. These plaques are a hallmark feature of Alzheimer's disease, and their accumulation is thought to play a key role in the development of the disease.

Memantine is used to treat moderate-to-severe Alzheimer’s disease by blocking NMDA receptors in the glutamatergic system. The drug was first synthesized by Eli Lilly and Company in 1968 as a potential agent to treat diabetes, and the NMDA activity was discovered in the 1980s. Memantine has been associated with a moderate decrease in clinical deterioration with only a small positive effect on cognition, mood, behavior, and the ability to perform daily activities in moderate-to-severe Alzheimer’s disease. There does not appear to be any benefit in mild disease.

## More about the Dataset
The dataset has 82 variables and 1080 observations. The variables include:

- `Mouse ID`
- The expression levels of 77 proteins with protein names followed by `"_n"` indicating that they were measured in the nuclear fraction.
- `Genotype`: control (c) or trisomy (t)
- `Treatment type:` memantine (m) or saline (s)
- `Behavior:` context-shock (CS) or shock-context (SC)
- `Class:` c-CS-s, c-CS-m, c-SC-s, c-SC-m, t-CS-s, t-CS-m, t-SC-s, t-SC-m
The expression levels of each protein were measured 15 times per mouse, and there were 72 mice in total. The dataset is in the form of a data frame, and each measurement was treated as an independent sample/mouse.

## Statistical analysis using the Mann-Whitney U test
The Mann-Whitney U test, also known as the Wilcoxon rank-sum test, is a non-parametric statistical test used to compare two independent groups of samples. It is commonly used in gene expression studies to compare the expression levels of genes between two discriminant groups. The Mann-Whitney U test is particularly useful in gene expression studies because gene expression data is often non-normally distributed and can have outliers, violating the assumptions of parametric tests such as the t-test. Overall, the Mann-Whitney U test is a valuable tool for gene expression studies as it allows for accurate and robust comparisons between groups, even in cases where the underlying distribution is unknown or non-normal.


## Installation and Setup
To get started with this project, you need to have Python 3.9 and conda installed on your computer. The Python packages used in this project are
- sklearn
- pandas
- seaborn
- matplotlib
- scipy
- plotly.express
- imblearn
- numpy 


