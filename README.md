# Group AA2 Final Project Proposal

## H1-B Visa Sponsorship During COVID-19

### Authors

| Name                   | Email Address        |
| -----------------------|----------------------|
| Jia Wu                 | jiawu123@uw.edu      |
| Yubin Cho              | yubinc@uw.edu        |
| Young You              | cuperido@uw.edu      |
| Brandon Lee Shen Thian | bthian01@uw.edu      |

### Date

Winter 2023

## Abstract

Our domain of interest is: “How has H1B sponsorship been affected during 2020-2022, the peak years of the COVID-19 pandemic?” As international students, answering this question is critical for others like us to develop a strategy should another world event disrupt the chances of attaining H1B sponsorship. To answer our main question, we plan to analyze H1B sponsor data to determine if there is a correlation between the number of sponsors that started, continued, and stopped sponsoring H1B visas across 2020-2022, to variables such as sponsors’ location and industry classification.

## Keywords

H1B visa, foreign worker, international student, COVID-19 pandemic, sponsorship

## Proposal

1. ### Introduction  

The world is gradually recovering from the COVID-19 pandemic, but is now beginning to deal with the aftermath effects. With the tech-layoffs starting in late 2022 possibly being attributed to the pandemic-induced recession, a heavily impacted group are those who are dependent on their jobs to remain in the United States. Specifically, affected H1-B visa holders are left scrambling to find their next job or be forced to leave the country. This concerning effect motivates us to conduct further analysis on how H1B sponsorship has been affected as the pandemic was ongoing during its peak years of 2020-2022. 

Our specific research questions include:
- How has the COVID-19 pandemic affected the number of H1-B visa sponsors from 2020-2022?
- Which states and cities contained the most sponsors that stopped sponsoring the most during the COVID-19 pandemic?
- Did companies in specific industries stop sponsoring H1-B visas the most during the COVID-19 pandemic?
- Do sponsors in certain locations have more H1-B approvals? How about denials?

Our main goal is to provide an insightful visualization and analysis of the sponsorship changes to foreign workers, international students, or others interested in obtaining a H1B visa. This is because the data can help these groups develop a strategy that can not only help them with eventual job searching, but also provide a sense of job security because they have developed a robust strategy. Furthermore, this topic resonates personally with our group because we are international students and can empathize with those who have been part of the layoffs. 


2. ### Related Work  

The economy has changed drastically during the pandemic, ultimately changing the job market for businesses and their employees. This shift is especially critical for those under a H1-B employment visa, considering that the most significant condition for a H1-B visa is the corporate sponsor. We can guess that there must have been a lot of changes to the sponsors of H1-B visas as well, and by looking into statistics on how much has changed during the pandemic, we expect to get the answers to our research questions.

We will refer to related reports and articles below to get a broader perspective and insight and to study the current practices of presenting and describing data according to statistics. First, The [H-1B Visa Program and Its Impact on the U.S. Economy](https://www.americanimmigrationcouncil.org/research/h1b-visa-program-fact-sheet) (American Immigration Council, 2022) research provides some specific examples (e.g., College Station, Texas), by comparing the number of approvals by year and region. Quoting the words of economists, they provide reasons as to why such a phenomenon occurred. We expect such research provides us with insight into our hypotheses. Secondly, the [How the H-1B Visa Works, in 5 charts](https://qz.com/india/1916876/your-questions-about-the-h2-b-visa-answered (Bhattacharya, 2020) article provides detailed charts for five questions, including which regions had the most sponsors and which industries issued the most H1 visas between 2018 and 2020. By comparing it with these statistics, we expect to be able to verify the data that we produce in the final project.

Also, [East Coast and Texas metros had the most H-1B visas for skilled workers](https://www.pewresearch.org/fact-tank/2018/03/29/h-1b-visa-approvals-by-us-metro-area/) (Ruiz & Krogstad, 2018) research shows a heat-map graph and a table about the percentage of H1 sponsors before the pandemic (2010-2016). We expect to learn how to give people general and intuitive graphs. By comparing situational data prior to our study period, we will also verify the logic of our conclusion to avoid a too-natural conclusion that applies to all general periods. Finally, [the H-1B Visa 2022-2023 Cap Season](https://www.immi-usa.com/h1b-visa-2018-cap/) (Saada, 2023) article explains the changes in national H1 visa approval rates from 2011 to 2022 and the brief reasons. We expect to be able to compare our data and verify whether we make a hypothesis that makes sense.


3. ### The Dataset

Our [datasets](https://www.uscis.gov/tools/reports-and-studies/h-1b-employer-data-hub/h-1b-employer-data-hub-files) are provided and collected by the U.S. Citizenship and Immigration Services (USCIS). The data was collected through submitted Form I-129's (a form submitted by employers which are required for a H1-B visa application) that were filed to USCIS or through adjudicative decisions. Across our target years of 2020 to 2022, there were a total of 176,028 observations, with each observation having 11 features. 

The core reason for providing the data was because of requests to USCIS to provide additional transparency to the inner workings of the H1-B program. These requests came from Congress, research institutions, the media, and the public. In particular, USCIS wants to make their data as available as possible so that potential employers and H1-B applicants can have a better understanding of the U.S. immigration system in order to comply with USCIS reporting mandates.

However, this dataset is not without its limitations and problems. As mentioned by USCIS, the creation of the dataset is done by manual entry of information from the Form I-129's to the computer. Firstly, this subjects the dataset to data entry errors due to human error. However, it is important to note that the information on Form I-129's may not necessarily be 100% correct. Therefore, the data on the forms may already contain false information such as incorrect employer name, tax ID, state, city, or ZIP code. Also, the dataset does not provide information on futher steps in the H1-B application process such as the lottery and the interview phase. Therefore, it likely is not an accurate representation of the number of successful H1-B applicants.

While analyzing this data, it is important to note a couple things. We must first acknowledge that there could be some stereotyping of the results. For example, states that sponsor less could be viewed as poorer or even racist. Next, it is very possible that the application approval process is subject to bias. Since a USCIS personnel is responsible for approving a H1-B application and has access to the applicant's information, we cannot disregard the potential and innate human biases that can come about from this.

4. ### Implications

Finding out the impact of the pandemic on H1-B sponsorship helps foreign workers and international students to gain insight into the overall status of the labor market and build strategies for adapting to the potential disruption they may face in obtaining opportunities for H1-B sponsorship.  We encourage that our information can be used to identify areas for improvement in the hiring and visa processes, which can benefit both businesses and foreign workers. Additionally, our research can assist governments and societies by allowing them to better understand the economic impacts of the pandemic. For example, the information can be used to help decide the appropriate policies and regulations to protect the labor market for foreign workers and support economic recovery. 

Also, the data can be used to inform policymakers about the need for targeted economic stimulus programs to help those affected by the pandemic. It could lead them to develop policies that can help reduce the negative impacts of the pandemic on foreign workers; including expanding access to other temporary work visas, increasing funding for job training and education programs, or creating additional economic incentives for employers to hire foreign workers.

5. ### Limitations & Challenges
There are two main limitations when it comes to our dataset: the accuracy of the data and the issue of racial discrimination.

We only have one dataset source which is from USCIS. Since we do not have additional sources, we cannot be sure or confirm the accuracy of the data. Furthermore, USCIS is an official government agency, and the data it showed might be modified by the government out of possible political reasoning. Thirdly, the data itself is uploaded through the applicant, petitioner, and requestor in paper form. There might be data entry from the paper form to the paper form from the staff, and possible errors on the form applicant filled in. Lastly, we know there is discrimination in certain fields, especially in tech companies. When it comes to H1B, however, we do not have race as an observation in the dataset, so it is hard for us to deal with race issues when we are looking for certain patterns for sponsorship in certain races. 

## Acknowledgements
We would like to thank our TA, Shachi Sonar, for approving the idea for our project!
