# Paper_Omega

In this repository, we provide the instances as well as the codes used in the paper "Integrated, hierarchical and interactive approaches for
the joint resolution of production lot-sizing and scheduling problems" submitted to the Omega journal. All the algorithms were implemented using AMPL programming language.

# Instance Generation

For the instance generation, we consider three different scenarios related to the processing and setup times, named Scenario 1, 2 and 3. Furthermore, three data distributions are used: Uniform, Normal and Poisson distributions. The codes "Generator_XX.txt" present the algorithms for instance generation for each of these cases.
The generated data are salved in the folders "DataXX". In these cases, "XX" indicates the scenario and distribution.
"U", "N" and "P" indicate the uniform, normal and poisson distribution, respectively.

# Algorithms

The files "IMCPH.txt", "IMTIPH.txt" and "ManneWarmStart.txt" present the integrated models, while "HSI.txt", "HSIIa.txt" and "HSIIb.txt" present the hierarchical strategies. "ISI.txt", "ISII.txt" and "ISIII.txt" are the interactive strategies. 
Furthermore, the files "ILS.txt" and "Local_Search.txt" are used in the hierarchical and interactive strategies.
The file "Infeasibilities.txt" saves the instances in which infeasibility occurs for each instance, which are the instances considered by the presented algorithms.
For "ManneWarmStart.txt" we need to specify which strategy resulted in better solutions. In this case, such information is provided in the files "beststrategyXX.txt".

Contact information:
Fernanda de Freitas Alves - fernandafalves@ufmg.br
