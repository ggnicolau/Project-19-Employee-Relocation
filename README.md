 <div align="center">
<img src="https://coursereport-production.imgix.net/uploads/school/logo/84/original/logo-ironhack-blue.png?w=200&h=200&dpr=1&q=75">
<img src="https://www.icmc.usp.br/noticias/5122-o-icmc-completara-50-anos-em-2021-e-ja-comecamos-os-preparativo">
</div>


<div align="left">

[![](https://readme-typing-svg.herokuapp.com/)](https://git.io/typing-svg)
</div>
<!--GITHUB_ACTIVITY:{"rows": 5}-->

---
<div align="center">

[![visitors](https://visitor-badge.glitch.me/badge?page_id=ggnicolau.visitor-badge)](https://badges.pufler.dev)
[![ggnicolau StackOverflow](https://stackoverflow-badge.vercel.app/?userID=15673147)](https://stackoverflow.com/users/15673147/ggnicolau)

![+5511976431347](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![ggnicolau](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![ggnicolau@usp.br](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)
![https://www.linkedin.com/in/ggnicolau/](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)
![Python 3.9](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![pgAdmin](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Atom](https://img.shields.io/badge/Atom-66595C?style=for-the-badge&logo=Atom&logoColor=white)
![Windows 10 Pro](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=ggnicolau&show_icons=true&theme=darcula)
</div>
<!--GITHUB_ACTIVITY:{"rows": 5}-->

---

<div align="left">
<div class=''text-justify''>

# Project-19-Employee-Relocation

 #### Data Analysis of Human Resource (HR) surveys collected from a company in need to relocate employees.

#### Libraries

pandas
numpy
sklearn
matplotlib
seaborn
plotly
squarify

#### Technologies
* Python version  3.9
* Git

#### Tools
* VS Studio
* Jupyter IPython

#### Services
* Github

## INTRODUCTION

Our **business problem** is about the need to improve the efficiency of human resources of a specific company using quantitative and computational approaches. For this, psychometric data were collected from employees from different areas of the company, in addition to the evaluation of their individual performances each semester.

The **objective** is to find out how we can fill the gaps in human resources for each sector. For this, our **hypothesis** is that we can find employees with underused skills in some sector and relocate them where they can be reused, especially in the most urgent sectors identified. For this, we opted for **methods** programming language _Python_.

## PART 1: Employees by sector and hiring

_1)_ To date, _1617 employees_ (CPFs) have worked at the company, divided into the following areas:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/funcion%C3%A1rios_por_setor_eng.png>
</div>

_2)_ The sectors that are least able to retain employees are _People_ and _Finance_ (almost half of the people left the sector or the company):

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/demiss%C3%B5es_por_setor_eng.png>
</div>

_3)_ Over time, many more employees were hired in the areas of operations, commercial and also, a little less, in the logistics sector; the rest remained more or less at the same level.

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/funcion%C3%A1rios_por_setor_por_per%C3%ADodo_eng.png>
</div>

It is probably a sales company. It started its activities in 2017 with approximately 70 employees per sector, evenly distributed. Over the next two semesters, hiring took place in the sectors that matter most to the business, such as operations and commercial (~600 employees) or logistics (~200 employees).

_4)_ When we look at the rate of hiring (and layoffs) over the semesters, we can see that the second semester was when more people were hired, focusing on the operations and commercial areas. In the following semester, he was hired mainly in the logistics sector.

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/tx_contrata%C3%A7%C3%A3o_por_setor_por_per%C3%ADodo_eng.png>
</div>

We can have a clearer view when we look at the accumulated rate of hiring between the second and last semester:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/tx_contrata%C3%A7%C3%A3o_acumulada_por_setor_por_per%C3%ADodo_eng.png>
</div>

_5)_ The other sectors remained practically stable in terms of the number of employees. The financial area, however, is the most unstable among the sectors; the total number of employees decreased in all periods, but there was a large circulation of employees – with a total of 84, but only 68 in the last period, while there were 77 in the first semester.

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/data/table1.png>
</div>

##

##

## PART 2: Performance _per_ Area

We already know the company&#39;s business revolves around sales and commerce, concentrating most of its human resources in these sectors, as well as the logistics necessary for the operational engineering of this process. On the other hand, we also know that some areas are having difficulty retaining their employees. From the analysis of the employees&#39; performance, we can know how to take better advantage of them in a way that leaves them satisfied, as well as translates into results for the company.

Users&#39; performance was classified from 1 to 3. With this we can identify employees who have obtained persistent unsatisfactory results over time and observe in their psychometric test if their skills are in accordance with the area or if it is better to transfer to another sector. Sometimes your best skills are underutilized and can be put to better use elsewhere.

Let&#39;s first look at the distribution of user performance by different sectors (operations, commercial, logistics, finance, people). It is predictable that if everything is working well, we will find a normal distribution of performances from grades 1 to 3.

1. _Operations:_

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/operations.png>
</div>

Observing 4 semesters, we notice that there is a period of progressive stabilization, from bad and generalized results in the first semester, until something regular. It is in the last two semesters that we notice a normal distribution. It is natural that the largest number of workers are at level 2, as this is the average we take as a standard for evaluating edges. However, we noticed that, despite the small increase in the number of employees, in the last semester the average increased and the proportion of employees with excellent performance (3) decreased to the same extent as those with poor performance (1).

We could then observe which employees had poor performance and some who had average performance (within an acceptable threshold), who have skills that can be better used in other areas.

1. _Commercial_:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/commercial.png>
</div>

In the commercial sector, practically the same logic was followed as in the operations sector. Probably after a period of adaptation and organization of the sector, the many employees who were hired in the sector for the initial period were adapting; In the end, there is a normal distribution of the performance of the sector&#39;s employees, with a little more prevalence of excellent performances over poor performances.

As in Operations, we could see which employees had poor performance and some who had average performance (within an acceptable threshold), which ones have skills that can be better used in other areas.

1. _Logistics_:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/logistics.png>
</div>

In logistics, our third largest area of ​​human resources commitment, the logic of progressive regularization of performances over the semesters was also followed. However, it is evident that there is an inefficiency in human resources. Although there are a good number of high-performing workers (3), it is the number of low-performing workers (1) that is of concern. Probably the grades are adequate, since it is an area that allows a more objective evaluation of the results.

This is the most relevant sector that we currently have and that requires intervention. In addition to being a strategic area with a lot of committed human resources, productivity is poorly distributed. We can see around 50 employees who can be redeployed based on their underutilized skills.

1. _Finance_:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/financial.png>
</div>

Finance is part of the two minority areas of the company, which is common in administrative areas. Also, performance evaluation can be more difficult to evaluate, because the results criteria are more intersubjective or also sensitive to externalities that are beyond the company&#39;s control. Also for this reason, it can be an area where there is greater circulation.

Our case is worrying. She never stabilized. It does not have any employee with optimal performance (3) as an example of what to follow in the area. All performed reasonably or poorly. It is an area that has a historic low in terms of employee permanence, the area already has few employees, but a few can be reallocated to other sectors. _The main thing, however, is that employees from other areas with exceptional skills can be brought in from other sectors where they are being underutilized, to stabilize the finance area_.

1. _People_:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/people.png>
</div>

It is the smallest sector of the company. It is usually more difficult to evaluate results, but we have more and more objective criteria for the sector. It has stabilized over the semesters, but still has a fair amount of poor performance compared to the amount of excellent performances. It also allows observing the relocation of these employees, but it already has few people and a lot of circulation.

## PARTE 3: Skills and Realocation

1. _Skills_

The company&#39;s employees answered psychometric questionnaires in which we can assess their various skills such as Reasoning, Social, Motivational and Cultural/Educational level. Through this data, we can create scores that allow **(a)** to objectively identify which skills are most required by area; **(b)** identify which are the possible reallocations, crossing with the performances of the workers and their respective current areas.

Observing the data, the best way we found was to look for the median of each of the _skills_ by area, in order to identify what is the highlight that is given by a reasonable worker to the area that differs from other areas._We also know that our most urgent area to watch is the_ **financial** , due to the poor performance that has not been resolved over time and the short stay of employees.

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/data/table2.png>
</div>

Thus, we observe that the highest cultural level is that of **people** followed by **financial** (urgent), requiring people with a higher educational level from other sectors to be relocated. In fact, the average employee most similar _across skills_ to **finance** is in the **people**. The jobs probably have a similar profile (more administrative), have similar number of employees, skills, educational level. A point of attention is that the people sector could also improve with some adjustments; another point is that, since both sectors have few employees, it is riskier to reallocate and transfer responsibilities.

The **commercial** and **logistics sectors** also seem to be interchangeable, since their average profile is similar, mainly requiring good _reasoning_, that is, a more technical and operational profile, sometimes more quantitative. In the case of **operations** , it seems to be more interchangeable with **logistics** , as it seems to require greater _Social_. In any case, they are interchangeable sectors that may have reallocation, especially after reallocation to other urgent services – but these sectors already seem to be performing in a measured way.

_We must, however, make an_ _ **important observation** __._ The data are unreliable and can lead to random or biased conclusions. There is a large variance between the values ​​of the columns and, to make matters worse, many of the important columns are practically empty (reaching **89%**) – normally, only the _Reasoning_ and _Culture_ are more complete. However, the completeness varies greatly between each area of ​​the company, which hinders the analysis. It&#39;s even worse when the amount of data varies between sectors that are of different sizes and some of them are quite small. Finally, it was not possible to validate whether our columns were calculated in the best way from the raw data and it was not possible to derive reliable thresholds to objectively determine which values ​​define the _skills_ for each sector.

1. _Self-Relocation: Nearest Neighbors (KNN)_

We tried to create a simple recommender system to automate relocation using a KNN (&#39;_k nearest neighbors_&#39;) model. However, as we said, the data does not seem to be adequate for this. We decided to take the smallest sample of our tables that contained as much information as possible to improve the model, but it was not enough.

We were able to verify the problem in the data just when we produced our model and tried to visualize it with our vectors (employees + skills) in a two-dimensional space. We can observe that the skill scores of our employees are all quite close or almost random, not translating into a good segregation to form clusters and therefore making it difficult to automate the identification of the best area for each employee (we can observe that we do not have well defined boundaries in our data).

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/pictures/distribution%20(1).png>
</div>

Our initial goal was to use the KNN model so that we could find employees who were on the boundary (_decision boundaries_) with other clusters, close to similar colleagues. The algorithm makes the prediction of each point by the similarity with the other points (nearest neighbors) using distance calculation (we use cosine similarity). For those on the frontier, the algorithm chooses a tiebreaker (there is no unclassified data point). When we ask to predict our data after the model is trained, as it uses distance calculation for prediction, it can sometimes break a tie by suggesting another classification that is not the original data point (in our case this would not exactly be an error) .

We then found 4 model suggestions for reallocation to the financial sector (our urgent area). Their scores are:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/data/table3.png>
</div>

As we can see, these are not adequate scores to improve the performance of a sector that is in trouble. Also, we don&#39;t believe we can trust the data for a good recommendation model. We understand that the best approach would not be through machine learning, but through an analytical task of interpreting the data.

1. _RESULTS: Relocation_

(a) _Experienced Employees_

Our first proposal is to look for company employees who had a _bad performance_ ( **1** ) in the last semester, but who have an educational level (_Culture_) and _Reasoning_ greater than **50 points**. We believe that these are candidates who have the capacity to deliver more - and are closer to the demands of our most urgent areas and with few employees (financial and people).

To speed up the work of finding the best candidates among our list, we sort first by _Culture_, then by _Reasoning_ and then by _Area_. We know how dedication to education requires a lot of time, financial resources and efforts. This means that the employee is likely to be dissatisfied with their situation, as their performance rating was low; considering how much he dedicated himself to his training, he would probably be more willing to relocate, being advantageous for the company and the employee. In addition, if your performance improves, it is possible that your experience will lead you to take on more responsibilities in the new sector and that new _leaders_, especially in the most needed sectors.

_With that alone we were able to return_ _**35**_ _possible candidates_. This is already a reasonable number for us to contact and evaluate the possibility of relocation. The ideal would be to seek employees from areas with more human resources, such as Operations, Commercial and Logistics, so as not to weaken smaller areas such as Finance and People. Below is the list ordered by importance to search for candidates:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/data/sompic.png>
</div>

(b) _New Employees_

We also chose to investigate new employees who have not yet had their performance evaluated. We believe that we can find promises that may be interested in a career acceleration program, given their skills and background. These professionals with great potential can compose the teams that will be restructured with more experienced employees of the company, in the sectors that demand this, such as Finance.

Since we have a complete profile of some, we identify those that have raw potential as a promise in the company. We found 13 candidates who are our promises and can be trained in the new teams:

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/data/mytable_4.png>
</div>

##

We also separated another 6 promises that we do not have their complete profiles, but that have a rare highlight in essential skills such as Reasoning and Culture, with scores always above 70% (very above average)

##

<div align="center">
<img src=https://github.com/ggnicolau/Project-19-Employee-Relocation/blob/main/data/mytable_3.png>
</div>

##

## CONCLUSION: Recommendations for Future Work

_Our first recommendation is to_ _**collect**_ _data and strengthen a data-centric culture_. It is important to understand _why_ workers do not finish _surveys_ and important columns are practically incomplete. Perhaps another approach is needed to ensure. It is also necessary that the _surveys_ are created with the help of the analysts and data scientists who will use them, to identify what and in what way is best to be collected. In addition, this approach allows for a better understanding and confidence in the data when it is analyzed, so that it can always be validated; with this we can have material for _verification and falsification of hypotheses based_ on the ability to reproduce experiments (reproducibility). Another important point is to create _**documentation**_ to allow standardization in the interpretation of data and continuity of analysis in a way that is less dependent on people. It is also necessary to _**standardize the data**_ and the database to facilitate the work.

_Once we have good data, we can move forward on attempts that have not yet been successful_. We can, for example, **identify exactly which CPFs are reliable candidates** for relocation and not just suggest which areas they might come from.

_Plus, once we have better data, we can_ _**model**_ _the relocation and hiring suggestion process_.We could, for example, create supervised models based on hierarchical classification algorithms such as _CatBoost_ to, given the characteristics of an employee, suggest which is the appropriate area to work. More than that, we could create more complex models than a KNN, or for other functions like finding the most similar employees who still don&#39;t collaborate together. Perhaps, create a _recommender system_. We could even establish _historical series_ or _forecasting_ if there was greater regularity in temporal data, as in the case of performance scores. If there is a text box for respondents to write, it is also possible to incorporate textual modeling through natural language processing.

_Finally, in the long term, a data culture would enable machine learning engineering to_ _**automate**_ _these processes on a recurring basis_, through the infrastructure of cloud services (_GCP, AWS, Gitlab_) where we can use tools like _CI/ CD, kubeflow, airflow, dataflow, mlflow, weight&amp;bias_ etc.

[1](#sdfootnote1anc) To consult these notes and others, open the Notebooks provided in the annex. Unfortunately, we haven&#39;t had the opportunity to refactor and modularize the code for better understanding and reproducibility, but you can find some explorations and insights in this POC (_Proof-of-Concept_). We chose here, therefore, to take advantage of the data that are most worked on and available, such as Culture and Reasoning, so as not to lose employees for relocation analysis. Also, both variables are important for reallocation to our most urgent sector: finance.

[2](#sdfootnote2anc) We believe, for example, that it would be interesting to incorporate basic data such as gender, color, sexual orientation, origin, to observe the plurality of teams or even encourage them, reaping the benefits of diversity.

## Version

0.0.5.0

## Author

* **Guilherme Giuliano Nicolau**: @ggnicolau (https://github.com/ggnicolau)

</div>

<!--GITHUB_ACTIVITY:{"rows": 5}-->

---

<div align="center">

<br/><br/>
![Quote](https://github-readme-quotes.herokuapp.com/quote?theme=dark&animation=grow_out_in)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ggnicolau&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

![https://medium.com/@ggnicolau](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)


</div>
