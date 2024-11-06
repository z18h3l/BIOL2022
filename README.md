java c
BIOL2022 Biology experimental design and analysis
Multivariate Assignment:
In groups, you will need to create your own non-biological multivariate system. Using this model system, come up with several (2 to 3) multivariate hypotheses relating to the assemblages of “species” in different “treatments” (2 factor design is encouraged) and the “habitat variables” that may be influencing “habitat use”. Make sure that your treatments are adequately replicated (you will need at least 3 of each treatment). You will need to make a sampling technique in your groups that will allow you to collect the data necessary to test your hypotheses. You should also decide who will coordinate the data preparation.
Each group will present a short (<5 min) presentation during the practical session in Week 10 (week 2 of the pracs). For this, you will have a short powerpoint presentation containing the following information. This is compulsory for this unit: This enables staff to give feedback so you can collect the appropriate data for analyses in the next 2 weeks. Note this feedback is meant to be friendly, we are not upset or angry if we point out flaws in your design.
● an introduction to your system (model species and your treatments);
● your hypotheses (there should be 2 or 3);
● a description of your taxonomy;
● your sampling design (including information on sampling effort and sample sizes);
● the habitat variables you will be measuring at each site (and how you will measure them);
● a map of your sites
Hypothesis 1: assemblages of ice cream in grocery stores in high income areas will be higher than assemblages of ice cream in grocery stores in low income areas.    
Hypothesis 2: assemblages of ice cream in grocery stores in malls will be higher than assemblages of ice cream in grocery stores in street stores.
Income heat map: https://www.microburbs.com.au/heat-map/average-income#151.20353944351947:-33.860889804419564:12 
Pop density heat map: https://www.microburbs.com.au/heat-map/population-density#151.2061608571312:-33.874142293283384:13 
Higher income:
Birch grove (income 1667, pop density 5397)
Darling point (income $1529, pop density 5704)
Clovelly (income $1493, pop density 5858)
Woollahra (income $1467, pop density 5615)
Lower income:
Campsie (income $559, pop density 6295)
Burwood (income $778, pop density 5140)
Rockdale (income $697, pop density 5790)
Belmore (income $618, pop density 4605)
Notes/feedback:
- Have 12 lists of habitat variables
- Replications of each combinations
- Not doing random replication
- Mix up map locations?
- Better design
- 
Multivariate Assignment
Introduction
● Aim of the experiment and hypotheses being tested
● Why is the study important and/or interesting
● Study system – species, location of experiment (brief)
Methods
● Set-up of experiment/survey
● Data / variables recorded and how
● Sampling design and justifications for analyses
● Statistical analyses used, including which are dependent/independent variable(s) (if applicable), unit of replication, actual test(s) and statistical package(s)
● Must include description of nMDS and PCA
Results
● Statement of results (data and stats). Refer to tables and figures as needed.
● Summary presentation of data (no raw data) as tables, figures or in text as appropriate.
● Use tables for large amounts of data where detail is important, use figures to illustrate patterns.
● Indicate sample size and errors, and note whether the latter are standard errors or standard deviations. Format consistently.
● Ev代 写BIOL2022 Biology experimental design and analysisPython
代做程序编程语言idence of thought in choices of analyses.
● Results of statistical analyses presented either in text, on figures, or in tables.
● Must include nMDS plot, ANOSIM or PERMANOVA, PCA Loadings Table, Scree Plot
Discussion
● Main conclusions or findings
● Interpretation of results – what do they mean? How do they relate to original aims?
● Limitations of approach or methods
● Future studies – what would you do next to improve what you did and/or extend the understanding of the subject?
General
● Brief Abstract at start of report
● Written in plain English
● Presentation (format/length)
● Summary of use of AI (prompts/conversations, AI platform) OR stated that no AI used
References
https://onlinelibrary.wiley.com/doi/full/10.1002/agr.21765
https://epubs.icar.org.in/index.php/IJDS/article/download/52943/pdf_246/152901
https://www.sciencedirect.com/science/article/pii/S0002916523050967 
Methods- how you reach PCA and then describe results
- How you use components, what criteria do you use to select important variables
Chose components from scree plot criteria- chose 1 and 2
- Component 1 is explained by …. (openness)
- Component 2 is explained by … (facilities)
Table showing important interactions
Score component 1:
Is openness going to differ between high income vs low income
Is openness going to differ between street and mall stores
- 2 factors = ANOVA
Results 1:
Significant effect of Location on openness
No effect of income on openness
- Visual representation with box plots - refer to stats with P values of ANOVA
Score component 2:
Are facilities going to differ between high vs low income
Are facilities going to differ between street and mall stores
Results 2:
Significant effect of income on facilities
No effect of Location on facilities
Simple linear regression to see if principle components predict diversity
JAMOVI ANALYSIS

Components
1. Checkouts and aisles
a. Name the variables in each components
2. Structures
3. Light intensity/open hours

- Sharp lines for component 1 and 2 but shallower for 3
- Argue to discard 3?
- =

- P value -> the factor’s significant effect on the components
Diss/SD -> which species coincidentally drove the differences 
- Top 3 species that drove the difference were chocolate, cookies and cream, and mango
- The most impact on assemblages

- The location had higher mean scores for component 1
PERMANOVA table of results
Unique
Source	df	    SS	    MS	Pseudo-F	P(perm) perms
In	 1	1548.3	1548.3	  1.7391	  0.114	   999
Lo	 1	2735.3	27 (35.3	  3.0723	  0.009	   996
InxLo	 1	852.04	852.04	 0.95703	  0.449	   997
Res	44	 39173	 890.3	        	       	      
Total	47	 44309    
SIMPER Test - 

Groups M    S
Average dissimilarity = 38.57
Group M	 Group S	       	       	        	     
Species	Av.Abund	Av.Abund	Av.Diss	Diss/SD	Contrib%	Cum.%
Chocolate	    1.67	    1.46	   3.18	   0.86	    8.24	 8.24
Cookies  Cream	    1.37	    0.95	   3.02	   0.89	    7.82	16.06
Mango	    1.21	    0.71	   2.94	   1.03	    7.61	23.67
Caramel	    1.14	    0.98	   2.89	   0.97	    7.49	31.17
Choc Chip	    0.96	    0.70	   2.87	   1.08	    7.43	38.60
Strawberry	    1.31	    0.90	   2.66	   0.90	    6.88	45.48
Mint	    1.05	    0.80	   2.57	   0.97	    6.67	52.16
Lemon	    0.75	    0.51	   2.51	   1.03	    6.52	58.68
Other	    1.59	    1.36	   2.51	   0.66	    6.51	65.19
Vanilla	    1.54	    1.36	   2.51	   0.81	    6.50	71.69



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
