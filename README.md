# Commitment-Model

Project Overview

This project analyzes customer commitment patterns at Crew's Cup, a rowing fitness company, to address customer churn challenges. Using a Five-Factor Commitment Model, the analysis aims to determine the most effective retention strategy among three options: ad campaign, new product line, or subscription model.

Dataset Description
Size: 1,500 customer records

Variables:

Commitment Items (15 variables):

•	Affective (a1-a3)

•	Normative (n1-n3)

•	Economic (e1-e3)

•	Forced (f1-f3)

•	Habitual (h1-h3)

•	Customer Intent (intent)

•	Treatment Groups

•	Demographics


Methodology

1. Factor Analysis

•	Validated five-factor commitment model

•	Analyzed factor loadings:

•	Habitual: 0.94

•	Normative: 0.90

•	Economic: 0.85

•	Affective: 0.83

•	Forced: 0.75

•	Explained 94.58% of total variance


2. K-means Clustering

Identified three distinct customer segments:

A.	The Faithful (26%): High affective and normative commitment

B.	Bargain Hunters (34%): Moderate economic commitment

C.	Fitness Buffs (40%): Lower overall commitment


3. Regression Analysis

Examined influence on repurchase intentions:

A.	Economic commitment: β = 0.0891 (p = 0.007)

B.	Affective commitment: β = 0.0557 (p = 0.040)


Key Findings

Factor Structure:

•	Strong validation of five-factor model

•	High reliability scores (Cronbach's α: 0.899-0.983)

•	Dominant factors explain significant variance

Customer Segmentation:

•	Clear segment identification

•	Distinct commitment patterns

•	Targetable customer groups


Commitment Impact:

•	Economic and affective commitment significant

•	Strong influence of habitual commitment

•	Clear hierarchy of commitment types


Strategic Recommendations

Implement Tiered Subscription Model:

A.	Leverage high habitual commitment

B.	Address economic value needs

C.	Target specific segments

Enhance Customer Experience:

A.	Focus on largest segment (Fitness Buffs)

B.	Build routine engagement

C.	Personalize offerings


Develop Community Programs:

A.	Utilize normative commitment

B.	Create social bonds

C.	Establish member recognition


Value Communication:

A.	Clear pricing structure

B.	Highlight benefits

C.	Emphasize long-term value


Installation and Usage

Clone the repository

git clone https://github.com/sameeragarwal123/Commitment-Model.git

This README provides a comprehensive overview of the project, its methodology, findings, and implementation details. It serves as both documentation and a guide for others who might want to understand or replicate the analysis.
