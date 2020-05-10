# Artificial Intelligence to the fight against Coronavirus (COVID-19)

COVID-19 disease was identified in December 2019 in China and declared a global pandemic by the WHO on 11 March 2020. 

After the declaration of the global pandemic, many AI experts have been tried to find how can be used Artificial Intelligence (AI) as a powerful tool in the fight against the COVID-19 pandemic. 

AI Technology, which includes Machine Learning (ML), Natural Language Processing (NLP), and Computer Vision technologies can be provided the automated intelligent capability as like as pattern recognition, explanation, and prediction. It can be useful to recognize (detect and diagnose) and predict COVID-19 infections

The purpose of this repository is providing the curated resource list of the state-of-the-art works on the field of AI(Aritificial Intelligence)/DL(Deep Learning) to the fight against COVID-19.

Contributions are welcome. Please contact us at hollobit@etri.re.kr / astaria82@gmail.com or send a pull request. You can have to add links through pull requests or create an issue which something I missed or need to start a discussion.

![AI application examples identified during the epidemic response phase](https://github.com/hollobit/COVID-19-AI/blob/master/AI%20to%20fight%20against%20COVID-19.png)

----
## Contents
* [Advice and guidance](#advice-and-guidance)
* [Associations](#associations)
  + [RSNA](#rsna) 
  + [IEEE](#ieee)
  + [HIMSS](#himss)
  + [SDOs](#sdos)
  + [Consortium](#consortium)
* [International Activity](#international-activity)
  + [EU](#eu)
  + [OECD](#oecd)
  + [Canada](#canada)
* [Standardization](#standardization)
* [Open Research and dataset](#open-research-and-dataset)
  + [CORD-19 Open Research Dataset](#cord-19-open-research-dataset)
  + [CORD-19 Related dataset](#cord-19-related-dataset)
  + [AWS Resources and programs supporting COVID-19 research](#aws-resrouces-and-programs-supporting-covid-19-research)
  + [Google Cloud COVID-19 public dataset program](#google-cloud-covid-19-public-dataset-program)
  + [2019 COVID-19 Data Set in Korean](#2019-covid-19-data-set-in-korean)
  + [Image datasets](#image-datasets)
  + [Open Datasets](#open-datasets)
  + [Models](#models)
  + [APIs](#apis)
  + [Github](#github)
  + [Lecture and course](#lecture-and-course)
  + [Tools](#tools)
* [Challenge](#challenge)
* [Paper index](#paper-index)
* [Review Paper and Report](#review-paper-and-report)
* [News and Resources](#news-and-resource)
* [Company and Product](#company-and-product)
  + [AI-assisted COVID-19 applications in Korea](#ai-assisted-covid-19-applications-in-korea)
  + [China](#china)
* [Miscellaneous](#miscellaneous)
----
## Advice and guidance
* [World Health Organization (WHO)](https://www.who.int/emergencies/diseases/novel-coronavirus-2019)
* [Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/coronavirus/2019-nCoV/)
* [European Centre for Disease Prevention and Control (ECDC)](https://www.ecdc.europa.eu/en/publications-data/guidance-wearing-and-removing-personal-protective-equipment-healthcare-settings)
* [National Institutes of Health (NIH)](https://www.nih.gov/health-information/coronavirus)
* [U.S. Food and Drug Administration (FDA)](https://www.fda.gov/emergency-preparedness-and-response/mcm-issues/coronavirus-disease-2019-covid-19-frequently-asked-questions)
* [Korea Centers for Disease Control and Prevention (KCDC)](http://www.cdc.go.kr/) COVID-19 Response Guidelines - [COVID Translate Project](https://covidtranslate.org/)

## Associations

### RSNA
* [Resources](https://www.rsna.org/covid-19)
* [Publications](https://pubs.rsna.org/2019-ncov)
* [Imaging Data Sharing Survey](http://bit.ly/rsna-covid-data)
* [Latest articles on COVID-19](https://www.european-radiology.org/highlights/covid-19/) by European Radiology

### IEEE
* [coronavirus spectrum](https://spectrum.ieee.org/tag/coronavirus)
* [COVID-19 fast track](https://app.smartsheet.com/b/form/c4990418a0d44e489ecf216424a2431d?utm_source=whatshappening_ask-image&utm_medium=hp&utm_campaign=ojemb)

### HIMSS
* [Coronavirus Updates](https://www.himss.org/news/coronavirus)
* [COVID-19 Digital Think Tank](https://www.himss.org/news/covid-19-digital-think-tank)

### BSTI
* The British Society of Thoracic Imaging (BSTI) have built a free to use, [anonymised and encrypted online portal](https://www.bsti.org.uk/training-and-education/covid-19-bsti-imaging-database/) to upload and refer imaging of patients with either confirmed or suspected COVID-19.

### CIFAR
* [Action on COVID-19](https://www.cifar.ca/action-on-covid19)

### SDOs
 * [American National Standards Institute](https://www.ansi.org/COVID-19/)
 
### Consortium
* [XPrize Pandemic Alliance](https://www.xprize.org/)- A DATA-POWERED ALLIANCE TO STOP COVID-19
* [C3.ai Digital Transformation Institute](https://c3dti.ai/)
* [Defeat Covid19 #defeatcovid19](https://www.defeatcovid19.org/) - [Introduction to the Group on GitHub](https://github.com/defeatcovid19) and first delivered [Pytorch solution for predictions on X-ray images of Covid-19 patients](https://github.com/defeatcovid19/defeatcovid19-net-pytorch).
* [The COVID-19 High Performance Computing Consortium](https://covid19-hpc-consortium.org/)

## International Activity
### EU 
* [AI-ROBOTICS](https://ec.europa.eu/digital-single-market/en/news/join-ai-robotics-vs-covid-19-initiative-european-ai-alliance)
* A EUROPEAN INITIATIVE [EU Imageing AI COVID-19](https://imagingcovid19ai.eu/) for Automated diagnosis and quantitative analysis of COVID-19 on imaging
* [AI and control of Covid-19 coronavirus](https://www.coe.int/en/web/artificial-intelligence/ai-and-control-of-covid-19-coronavirus) by Council of Europe
### OECD
* [AI-powered COVID-19 watch](https://oecd.ai/covid)
### Canada
* [AI Against COVID-19 Canada](https://ai-against-covid.ca/)
### WHO
* [Global research on coronavirus disease (COVID-19)](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/global-research-on-novel-coronavirus-2019-ncov)

## Standardization
### ITU-T/WHO FG-AI4H
* Proposed ad-hoc working group on AI for COVID-19 

### HL7 FHIR
* SANER project - enable the secure and rapid transfer of information about hospital bed capacity and availability of critical resources during public health emergencies. 
   * [HL7 International and Audacious Inquiry Collaborate to Support COVID-19 Response](https://www.heraldmailmedia.com/news/state/hl7-international-and-audacious-inquiry-collaborate-to-support-covid-19-response/article_613a86c7-febd-5f19-a553-e7d8776bae18.html)
   * [Interview With Audacious Inquiry on SANER Project, PULSE-COVID Edition](https://www.hcinnovationgroup.com/interoperability-hie/fast-healthcare-interoperability-resources-fhir/article/21135564/interview-with-audacious-inquiry-on-saner-project-pulsecovid-edition)
   * Project summary - [Situation Awareness for Novel Epidemic Response (SANER) FHIR IG (PSS in Confluence)](https://www.hl7.org/special/Committees/projman/searchableProjectIndex.cfm?action=edit&ProjectNumber=1617)
   * [HL7/fhir-saner](https://github.com/HL7/fhir-saner) @ github
   * [Implementation Guide](http://build.fhir.org/ig/HL7/fhir-saner/overview.html) of Situational Awareness for Novel Epidemic Response
   
* COVID-19 project 
   * [COVID 19 FHIR IG (PSS in Confluence)](https://www.hl7.org/special/Committees/projman/searchableProjectIndex.cfm?action=edit&ProjectNumber=1620)
   * [Logica Implementation Guide: Covid-19)(https://confluence.hl7.org/display/CR/COVID-19+Response+Home)
### HealthIT.gov
* [Interoperability for COVID-19 Novel Coronavirus Pandemic](https://www.healthit.gov/isa/covid-19)
   * [CDC - New ICD-10-CM code for the 2019 Novel Coronavirus (COVID-19)](https://www.cdc.gov/nchs/data/icd/Announcement-New-ICD-code-for-coronavirus-2-20-2020.pdf)
   * [CDC Coding Guidance for 2019 Novel Coronavirus (COVID-19)](https://www.cdc.gov/nchs/data/icd/Announcement-New-ICD-code-for-coronavirus-3-18-2020.pdf) - changing effective date for reporting to April 1, 2020
   * [HL7 COVID-19 Response Home](https://confluence.hl7.org/display/CR/COVID-19+Response+Home) - including link to COVID-19 FHIR v4 IG
   * [SNOMED CT Coronavirus new and existing codes](https://confluence.ihtsdotools.org/display/snomed/SNOMED%2BCT%2BCoronavirus%2BContent)
   * [PHIN VADS COVID-19 Informatics Resources](https://phinvads.cdc.gov/vads/SearchVocab.action)
   
## Open Research and dataset

### CORD-19 Open Research Dataset
* [Call to Action to the Tech Community on New Machine Readable COVID-19 Dataset](https://www.whitehouse.gov/briefings-statements/call-action-tech-community-new-machine-readable-covid-19-dataset/)
* [CORD-19](https://pages.semanticscholar.org/coronavirus-research)

### CORD-19 Related dataset
* [COVID-19 Research Database](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/global-research-on-novel-coronavirus-2019-ncov) (provided by the WHO)
* [LitCOVID](https://www.ncbi.nlm.nih.gov/research/coronavirus/) (provided by the NIH)
* [COVID-19 Resource Page](https://aka.ms/AA7q3eb) and [CORD-19 AI Powered Search](https://covid19search.azurewebsites.net/) (provided by Microsoft)
* [COVID-19 Research Export File](https://docs.google.com/spreadsheets/d/1-kTZJZ1GAhJ2m4GAIhw1ZdlgO46JpvX0ZQa232VWRmw/edit#gid=2034285255) (provided by Dimensions)
* [Day-Level COVID-19 Dataset](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset) (hosted on Kaggle)
* [COVID-19 Global Cases](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) (provided by Johns Hopkins University)
* [COVID-19 Open Patent Dataset](https://about.lens.org/covid-19/) (hosted by Lens.org)
* [COVID-19 Global Rheumatology Registry](https://rheum-covid.org/) (provided by the Global Rheumatology Alliance)
* [COVID-19 Literature Review Collection](https://www.cochranelibrary.com/covid-19) (hosted by Cochrane Library)
* [CORD-19 Search Engine](https://cord19.vespa.ai/) (provided by [Verizon Media](https://yahoodevelopers.tumblr.com/post/613846232270553088/search-covid-19-open-research-dataset-cord-19))
* [Blog Post: Computer Scientists Are Building Algorithms to Tackle COVID-19](https://onezero.medium.com/amp/p/f4ec40acdba0)
* [CORD-19 on FHIR](https://github.com/fhircat/CORD-19-on-FHIR)
* [Covid-19 Semantic Browser](https://github.com/gsarti/covid-papers-browser): Browse Covid-19 & SARS-CoV-2 Scientific Papers with Transformers

### CORD-19 Related tools
* [Neural Covidex](https://covidex.ai/): AI-based ranking of biomedical studies.
* [CovidScholar](https://www.covidscholar.com/): Adaptation of MatScholar optimized for COVID-19.
* [COVID-19 Explorer](http://covidexplorer.in/): Search filter developed by Indian researchers.
* [COVID-19 Search](https://covid19search.azurewebsites.net/): Powered by Microsoft’s Azure Cognitive Search.
* [Covid Graph](https://covidgraph.org/): Knowledge graph created by a German-based team.
* [CoViz](https://coviz.apps.allenai.org/): Visualization tool developed at AI2.
* [CovidAsk](https://covidask.korea.ac.kr/): Question-answering tool created in South Korea.
* [Vespa](https://cord19.vespa.ai/): Verizon Media’s search engine, optimized for CORD-19.
* [ASReview](https://github.com/asreview/asreview-covid19): CORD-19 plugin for ASReview software.
* [CORD-19 Demos and Resources](https://discourse.cord-19.semanticscholar.org/t/cord-19-demos-and-resources/132): Semantic Scholar’s list of tools.

### AWS Resources and programs supporting COVID-19 research:
* [AWS Diagnostic Development Initiative Web Portal](https://aws.amazon.com/government-education/nonprofits/disaster-response/diagnostic-dev-initiative/)
* [Registry of Open Data on AWS, COVID-19 Open Research Dataset (CORD-19)](https://registry.opendata.aws/cord-19/)
 
### Google Cloud COVID-19 public dataset program
* [Press release](https://cloud.google.com/blog/products/data-analytics/free-public-datasets-for-covid19) - [Get Start](https://console.cloud.google.com/marketplace/details/bigquery-public-datasets/covid19-public-data-program?_ga=2.83757014.-19881939.1585612997)
 
### 2019 COVID-19 Data Set in Korean
* [한국어 Dataset](https://www.kaggle.com/yjunwoo14/2019-covid19-ncov19-data-set-in-korean?fbclid=IwAR2PblMtQSDR25QS_xLO7KqucZVdU2qo2cWgYR_k3thvrvHV9D5Sdx8VEfE)

### Image datasets
* [MosMedData: COVID19_1000 Dataset:](https://mosmed.ai/en/) Chest CT Scans with COVID-19 Related Findings
* [RxRx19](https://www.rxrx.ai/rxrx19): The First Morphological Imaging Dataset on SARS-CoV-2 Virus
* [RadiologyAi Consortium](https://www.radiologyaiconsortium.org/) - Repository of crowd-sourced CT Scans of COVID-19 patients
* [Società Italiana di Radiologia Medica e Interventistica](https://www.sirm.org/category/senza-categoria/covid-19/)
* [Cohen COVID-19 open dataset (X-rays, CTs)](https://github.com/ieee8023/covid-chestxray-dataset)
* [Cohen COVID-19 crowed-sourcing annotation project](https://towardsdatascience.com/covid-19-imaging-dataset-chest-xray-ct-for-annotation-collaboration-5f6e076f5f22?fbclid=IwAR1U_kov2vIc3C9bjCN6vqqfdR1BIm4HXDIQoZqHLGkGn0DuFnlEFUSbUv0)
* [UCSD-AI4H COVID-19 open dataset](https://github.com/UCSD-AI4H/COVID-CT) - a COVID-19 CT scan dataset which contains 349 COVID-19 CT images from 216 patients and 397 non-COVID CT images.
* [100 segmented axial CT slices from ~60 Italian patients](http://medicalsegmentation.com/covid19/)
* [Radiopaedia](https://radiopaedia.org/articles/covid-19-3)
* [X-Rays images of ~30k unique patients having pulmonary diseases](https://www.kaggle.com/nih-chest-xrays/data)
* [X-Rays images of pneumonia affected pediatric patients](https://www.kaggle.com/andrewmvd/pediatric-pneumonia-chest-xray)
* [X-Rays images of pneumonia affected patients](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
* [X-Rays and CT scan images of patients affected by different kind of pneumonias (including COVID)(https://radiopaedia.org/search?lang=us&q=pneumonia&scope=cases)
* [AI system for the automatic diagnosis of COVID-19 pneumonia from ultrasound images](https://www.disi.unitn.it/iclus) by University of Turin

### Open Datasets 
* [the collection of datasets from various clinical studies](http://www.covidanalytics.io/dataset) by The Operation Research and Analytics Lab from MIT
* [google dataset search](https://datasetsearch.research.google.com/search?query=coronavirus%20covid-19&docid=c7BnT6bakuzvP2kAAAAAAA%3D%3D)
* [California COVID-19 Hospital Data and Case Statistics](https://data.chhs.ca.gov/dataset/california-covid-19-hospital-data-and-case-statistics)
* [US COVID-19 Daily Cases with Basemap](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HIDLTK) by Harvard
* [Data on the geographic distribution of COVID-19 cases worldwide](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide) by European Centre for Disease Prevention and Control
* [COVID-19 Italy – Situation monitoring](https://github.com/pcm-dpc/COVID-19)
* [Coronavirus COVID-19 Cases Data for China and the Rest of the World](https://data.humdata.org/dataset/coronavirus-covid-19-cases-data-for-china-and-the-rest-of-the-world)
* [ACAPS COVID-19: Government Measures Dataset](https://data.humdata.org/dataset/acaps-covid19-government-measures-dataset)
* [World Bank Indicators of Interest to the COVID-19 Outbreak](https://data.humdata.org/dataset/world-bank-indicators-of-interest-to-the-covid-19-outbreak)
* [The COVID Tracking Project collects and publishes the most complete testing data available for US states and territories.](https://covidtracking.com/data)
* [Social Distancing Scoreboard](https://www.unacast.com/covid19/social-distancing-scoreboard) by Unacast
* [New York City COVID-19 Dataset](https://www1.nyc.gov/site/doh/covid/covid-19-data.page)
* [Definitive Healthcare Public COVID-19 Data Repository](https://github.com/rsowers-dhc/covid19)
* [A Public data lake for analysis of COVID-19 data](https://aws.amazon.com/blogs/big-data/a-public-data-lake-for-analysis-of-covid-19-data/)
* [CAS COVID-19 Antiviral Candidate Compounds Dataset](https://www.cas.org/covid-19-antiviral-compounds-dataset)
* [HIRA COVID-19 opendata](https://covid19data.hira.or.kr)
* [open source COVID-19 glossary](http://open-source-covid-19.weileizeng.com/world)
* [C3.ai COVID-19 Data Lake](https://c3.ai/covid/) is a unified, open data image of critical COVID-19 data publicly available at no cost to the global research community beginning on April 13, 2020. C3.ai COVID-19 Data Lake data sets will initially include:
  * [Johns Hopkins University: COVID-19 Data Repository](https://github.com/CSSEGISandData/COVID-19)
  * [The Atlantic: COVID Tracking Project](https://covidtracking.com/)
  * [The New York Times: COVID-19 Data in the United States](https://github.com/nytimes/covid-19-data)
  * [nCoV-2019 Data Working Group: Epidemiology Data](https://github.com/beoutbreakprepared/nCoV2019/tree/master/latest_data)
  * [MOBS Lab: COVID-19 Situation Report](https://www.mobs-lab.org/2019ncov.html)
  * [World Health Organization: Daily Situation Reports](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports)
  * [European Centre for Disease Prevention and Control: Worldwide Situation Updates](https://www.ecdc.europa.eu/en/novel-coronavirus-china)
  * [University of Montreal: COVID-19 Image Data Collection](https://github.com/ieee8023/covid-chestxray-dataset)
  * [National Center for Biotechnology Information Virus Database](https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/virus?SeqType_s=Nucleotide&VirusLineage_ss=Severe%20acute%20respiratory%20syndrome%20coronavirus%202,%20taxid:2697049)
  * [COVID-19 Open Research Dataset (CORD-19)](https://registry.opendata.aws/cord-19/)
* Additional datasets, to be published May 15, 2020, will include:
  * [Data Science for COVID-19 (DS4C): South Korea Dataset](https://github.com/ThisIsIsaac/Data-Science-for-COVID-19)
  * [Indian Ministry of Health & Family Welfare: COVID-19 India](https://www.mohfw.gov.in/)
  * [Sito del Dipartimento della Protezione Civile – Emergenza Coronavirus](https://github.com/pcm-dpc/COVID-19)
  * [Data Science for COVID-19 Indonesia Initiative](https://www.kaggle.com/ardisragen/indonesia-coronavirus-cases)
  * [Kaiser Health: US Hospital ICU Beds](https://khn.org/news/as-coronavirus-spreads-widely-millions-of-older-americans-live-in-counties-with-no-icu-beds/#lookup)
  * [HealthData.org: US Hospital Capacity](https://covid19.healthdata.org/projections)
  * [Environment Protection Agency: US Air Quality](https://aqs.epa.gov/aqsweb/documents/data_api.html)
  * [New York ISO: Electricity Load Data](https://www.nyiso.com/custom-reports)
  * [US Census Bureau: Population Data](https://data.census.gov/cedsci/)
  * [IEEE: COVID-19 Tweets Dataset](https://ieee-dataport.org/open-access/corona-virus-covid-19-tweets-dataset)
  * [University of Washington: COVID-19 Projections](https://covid19.healthdata.org/)
  * [Kaiser Family Foundation: Social Distancing Policies](https://www.kff.org/health-costs/issue-brief/state-data-and-policy-actions-to-address-coronavirus/#socialdistancing)
 * [Coronavirus (COVID-19) Resources](https://data.world/resources/coronavirus/) by data.world
 * [Comprehensive Covid-19 resources from ESRI/GIS](https://coronavirus-resources.esri.com/)
 * [Covid-19 - fast.ai forum](https://forums.fast.ai/c/covid-19)
 * [Auto-updated Dashboards](https://covid19dashboards.com/) built using fastpages and updated using github actions, from above JHU data
 * [LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/?utm_source=Nature%20Briefing&utm_campaign=2033dfb840-briefing-dy-20200318&utm_medium=email&utm_term=0_c9dfd39373-2033dfb840-43229289) is a curated literature hub for tracking up-to-date scientific information about the 2019 novel Coronavirus
 * [100+ million COVID-19 Twitter dataset and pre-processing scripts](https://github.com/thepanacealab/covid19_twitter) @github - [Covid-19 Twitter chatter dataset] for scientific use(http://www.panacealab.org/covid19/)

### Models 
 * [Alibaba - Trained on data and CT scans from more than 5,000 confirmed cases](https://aimi.stanford.edu/resources/covid19)
 * [Canon/Vital Images](https://global.medical.canon/products/healthcare_it/clinical_application/ct_lung_analysis) - Lung CT model that Includes detection of ground glass nodules
 * [Infervision](https://www.wired.com/story/chinese-hospitals-deploy-ai-help-diagnose-covid-19/) - Trained on 5,000 confired cases; deployed at 34 hospitals in China
 * [RadLogics / Univ of Maryland (Eliot Siegel)](https://arxiv.org/abs/2003.05037) - 2D and 3D deep-learning models for thoracic CT studies; quantifies and tracks disease burden
 * [Riverain](https://www.riveraintech.com/clearread-ct/) - Lung CT model that Includes detection of ground glass nodules
 * [Tianjin Medical Univ Cancer Institute and Hospital](https://www.medrxiv.org/content/10.1101/2020.02.14.20023028v3.full.pdf+html) - Model to predict COVID-19 vs. typical viral pneumonia ahead of the pathogenic test
 * [COVID-Net](https://medium.com/@sheldon.fernandez/covid-net-an-open-source-neural-network-for-covid-19-detection-48b8a55e6d44) by Darwin AI & Univ of Waterloo
 
### APIs
* [ProgrammableWeb's Coronavirus category](https://www.programmableweb.com/category/coronavirus)
* [Postman COVID-19 API Resource Center](https://covid-19-apis.postman.com/)
* [Open-Source-COVID-19](http://open-source-covid-19.weileizeng.com/) - A global collection of Open Source projects during COVID-19

### Github
* [Open-Source-COVID-19 @ Github](https://github.com/WeileiZeng/Open-Source-COVID-19)
* [public repositories matching COVID-19 topic @ Github](https://github.com/topics/covid-19)
* [2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins](https://github.com/CSSEGISandData/COVID-19)
* [COVID-Net Open Source Initiative](https://github.com/lindawangg/COVID-Net)
* [PyTorch implementation of COVID-Net](https://github.com/IliasPap/COVIDNet)
* [Tracking the growth of COVID-19 Cases worldwide](https://github.com/aatishb/covidtrends) - [website](https://aatishb.com/covidtrends/)
* [Code for modelling estimated deaths and cases for COVID19](https://github.com/ImperialCollegeLondon/covid19model)
* API & Webapp to [answer questions about COVID-19](https://github.com/deepset-ai/COVID-QA). Using NLP (Question Answering) and trusted data sources.
* [Chest X-ray and CT datasets](https://github.com/arthurfigueiredo/covid-dataset)
* [An image based CT attempt at coronavirus2019 (covid19) diagnosis](https://github.com/JordanMicahBennett/SMART-CT-SCAN_BASED-COVID19_VIRUS_DETECTOR)

### Lecture and course 
* [AI for Healthcare in the Time of COVID-19](https://www.udacity.com/ai_in_healthcare/virtual_conference) @ Udacity - May 12 ~ 13
* [Vaxopedia](https://vaxopedia.org/2020/03/11/covid-19-presentations-and-webinars/) - COVID-19 presentation and webinar links
* [CS472 Data science and AI for COVID-19](https://sites.google.com/view/data-science-covid-19/homepage?authuser=0) - Standford
* [Find my virus: Mobilising AI and big data to fight COVID-19](https://www.bruegel.org/events/find-my-virus-ai-can-help-track-corona-but-are-we-giving-up-privacy/)
* Online Workshop on [Covid19@ELLIS](https://ellis.eu/covid-19) on April 1st 
* [COVID-19 and AI: A Virtual Conference](https://hai.stanford.edu/events/covid-19-and-ai-virtual-conference/overview) by HAI, April 1, 2020 - [Agenda](https://hai.stanford.edu/events/covid-19-and-ai-virtual-conference/agenda), [Video Archive](https://youtu.be/z4105Exe23Q) 

### Tools
* [CovidWatcher](https://covidwatcher.dbmi.columbia.edu/) - a research tool built by Columbia University and powered by people around the United States
* [Understanding and tracking our progress against COVID-19](https://www.microsoft.com/en-us/ai/ai-for-health-covid-data) by Microsoft 
* [COVID-19 Prediction in US, CA using Tableau](http://www.calstatela.edu/centers/hipic/covid-19-us-ca-confirmed-prediction)
* [Corona calculator](https://corona-calculator.herokuapp.com/), a tool that helps to visualize the impact of social distancing
* DeepMind has [released structure predictions](https://deepmind.com/research/open-source/computational-predictions-of-protein-structures-associated-with-COVID-19) of several under-studied proteins associated with SARS-CoV-2
* [Neural Covidex](https://covidex.ai/) applies state-of-the-art neural network models and artificial intelligence (AI) techniques to answer questions using the COVID-19 Open Research Dataset (CORD-19) - ([github source](https://github.com/castorini/covidex))
* [COVID-19 Tools](http://surf.stanford.edu/covid-19-tools/) by SURF Stanford Medicine
* [Covid-19 Data Explorer](https://covid19.cwerner.ai/) - Web-app built from Streamlit
* [Impressive visualizer of country numbers](https://boogheta.github.io/coronavirus-countries/)
* [Covid19 Tracker - US ONLY!](https://covidtracking.com/)
* [Microsoft covid19 tracker](https://www.bing.com/covid) - but no raw data
* [outbreak simulation](https://meltingasphalt.com/interactive/outbreak/)
* Scale-AI will provide [free data-labeling/annotation service for researchers working](https://scale.com/blog/scale-ai-covid-19-research) with [[covid19]] datasets
* [ACES Pandemic Tracker](https://www.kflaphi.ca/aces-pandemic-tracker/)
* [Data4Covid19](https://www.data4covid19.com/) is a non-profit project created with the aim of making people aware of the spread of the SARS-CoV-2 virus within many countries through the use of data.
* [COVID-19 Sounds App](https://www.covid-19-sounds.org/en/#) - The aim of this research is to collect data to inform the diagnosis of COVID-19 by developing machine learning algorithms, based primarily on sounds of their voice, their breathing and coughing.

## Challenge
* [COVID-19 HACKATHONS](https://www.bigdive.eu/covid19-hackathons/)
* [COVID-19 Online Hack](https://www.teensinai.com/hackathons/covid-19-hackathon/) #youthvsCOVID #TeensInAI #AIForGood
* [AI Rapid Response to the Coronavirus Pandemic](https://lumiatacovid19.devpost.com/) - LUMIATA COVID-19 GLOBAL AI HACKATHON
* *[India’s COVID-19 Online Hackathon](http://coronathon.in), from March 22 – April (on-going)*
* *[#EUvsVirus](https://euvsvirus.org), April 24-26*
* [CLAIRE Taskforce on COVID19](https://covid19.claire-ai.org/initiatives) (on-going) 
* [COVID-19: Forecasting The Corona Outbreak](http://machinehack.com/course/covid-19-forecasting-the-corona-outbreak/Rules) (open) 
* [Hack the crisis in India](http://hackacause.in) (open) 
* [UNCOVER COVID-19 Challenge](https://www.kaggle.com/roche-data-science-coalition/uncover)
* [COVID-19 Open Research Dataset Challenge (CORD-19)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge?fbclid=IwAR1d_P_F42k-SJFZQk1LlHkN5m9vyB3WV8R3qt0nRb7TAwpvrBLNlc2R5do)
* [COVID19 Global Forecasting (Week 1)](https://www.kaggle.com/c/covid19-global-forecasting-week-1) - closed
* [COVID19 Global Forecasting (Week 2)](https://www.kaggle.com/c/covid19-global-forecasting-week-2)
* [월간 데이콘 4 코로나 데이터 시각화 경진대회](https://dacon.io/competitions/official/235590/overview/?fbclid=IwAR12vVjbOYFgvUNKk6o-8Scds_whPw2qcla8uaUbpnVlaRF9D6eAwVjHI6c)
* Immediate First [Call for Proposals AI Techniques to Mitigate Pandemic](https://c3dti.ai/research/applying-ai-to-mitigate-the-covid-19-pandemic/)
* Hackathon : [COVID-19 : Forecasting The Corona Outbreak](https://www.machinehack.com/course/covid-19-forecasting-the-corona-outbreak/) by machinehack 
* Hackathon : [Hack For WuHan](https://community.wuhan2020.org.cn/en-us/hackathon/index.html)
* [covid-19-hackathon](https://github.com/aiformankind/covid-19-hackathon) @github
* [Hackathon : CORONAHACK - AI VS. COVID-19](https://www.hackathon.com/event/coronahack---ai-vs-covid-19-99337559314)
* [COVID-19 global AI hackathon](https://www.innovatorsmag.com/covid-19-global-ai-hackathon/)

## Paper index
* [BioMed Sanity](http://biomed-sanity.com/?fbclid=IwAR2VLUMQDtid1r90vW7241eqTx3YMnPt5pCPyha0Rieku6-EaAQtWaLKF9E)
* [RSNA COVID-19](https://pubs.rsna.org/2019-ncov)
* COVID-19 search results from [medrXiv](https://www.medrxiv.org/search/COVID)
* COVID-19 SARS-CoV-2 preprints from [arXiv](https://arxiv.org/covid19search)
* COVID-19 SARS-CoV-2 preprints from [medRxiv and bioRxiv](https://connect.biorxiv.org/relate/content/181)
* [Google scholar COVID-19](https://scholar.google.com/scholar?q=COVID-19)
* [related article archive](https://pages.semanticscholar.org/coronavirus-research)
* [Coronavirus (Covid-19)](https://www.nejm.org/coronavirus) by NEJM(New England Journal of Medicine)
* [CARING By Mahajan Imaging](https://caring-research.com/list-of-all-radiology-papers-related-to-coronavirus/) - Resource tracking COVID-19 papers on radiology of COVID-19 with numbers.  Updated frequently!
* [Doctor Penguin](http://doctorpenguin.com/covid19) - Resource tracking COVID-19 papers, research and publications.  Updated frequently!

## Call for Papers
* [Call for Papers - Special Issue on Artificial Intelligence and Information Technologies for COVID-19](http://www.techscience.com/ndetail/covid-19), Computers, Materials & Continua (CMC)

## Review Paper and Report
* [Mapping the Landscape of Artificial Intelligence Applications against COVID-19](https://arxiv.org/abs/2003.11336)
* [Modified SEIR and AI prediction of the epidemics trend of COVID-19 in China under public health interventions](http://jtd.amegroups.com/article/view/36385/pdf)
* [Report of the WHO-China Joint Mission on Coronavirus Disease 2019 (COVID-19)](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf)
* [Digital technology and COVID-19](https://www.nature.com/articles/s41591-020-0824-5)
* [Rapid AI Development Cycle for the Coronavirus (COVID-19) Pandemic: Initial Results for Automated Detection & Patient Monitoring using Deep Learning CT Image Analysis](https://arxiv.org/abs/2003.05037)
* [Towards an Artificial Intelligence Framework for Data-Driven Prediction of Coronavirus Clinical Severity](https://www.techscience.com/cmc/v63n1/38464)
* RSNA Publishes [Expert Consensus on COVID-19 Reporting](https://pubs.rsna.org/doi/10.1148/ryct.2020200152)

## News and Resources
* May 10
  * [How AI use cases are evolving in the time of COVID-19](https://www.healthcareitnews.com/news/how-ai-use-cases-are-evolving-time-covid-19)
  * [Could AI solve the COVID-19 crisis?](https://jaxenter.com/could-ai-solve-the-covid-19-crisis-171471.html)
  * **[FDA permits use of Aidoc’s AI to detect ‘incidental findings’ associated with COVID-19](https://venturebeat.com/2020/05/08/aidoc-obtains-fda-clearance-for-ai-that-uses-ct-scans-to-help-diagnose-covid-19/)**
  * [AI researchers seeking COVID-19 answers face hurdles](https://www.rollcall.com/2020/04/28/ai-researchers-seeking-covid-19-answers-face-hurdles/)
  * [Drug research turns to artificial intelligence in COVID-19 fight](https://biv.com/article/2020/05/drug-research-turns-artificial-intelligence-covid-19-fight)
  * [AI precision medicine mining finds 13 human COVID-19 risk genes](https://www.healtheuropa.eu/ai-precision-medicine-mining-finds-13-human-covid-19-risk-genes/99851/)
  * [AI Is Screening Billions of Molecules for Coronavirus Treatments](https://www.the-scientist.com/news-opinion/ai-is-screening-billions-of-molecules-for-coronavirus-treatments-67520)
  * [AI Predicts New COVID-19 Drugs, New Commercial COVID-19 Command Center](http://www.bio-itworld.com/2020/05/ai-predicts-new-covid-19-drugs-new-commercial-command-center.aspx)
  * [How AI Is Accelerating Drug Development for COVID-19](https://www.datanami.com/2020/05/08/how-ai-is-accelerating-drug-development-for-covid-19/)
  * [Medical AI Startup Quickly Shifts Strategy to Fight COVID-19 Pandemic](https://www.aithority.com/technology/life-sciences/medical-ai-startup-quickly-shifts-strategy-to-fight-covid-19-pandemic/)
  * [The Touch-Free World: New Voice Business Opportunities Post-Coronavirus](https://voicebot.ai/2020/05/09/the-touch-free-world-new-voice-business-opportunities-post-coronavirus/)
  * [AI Flags High-Risk COVID-19 Patients](https://aidaily.co.uk/articles/ai-flags-high-risk-covid-19-patients)
  * [AI in the times of corona: Robots can reduce human contact, transmission of Covid-19](https://economictimes.indiatimes.com/magazines/panache/ai-in-the-times-of-corona-robots-can-reduce-human-contact-transmission-of-covid-19/articleshow/75645277.cms)
  * [AI models suggest masking policy more cost-effective than lockdown](https://news.cgtn.com/news/2020-05-09/AI-modeling-shows-mask-effective-in-COVID-19-prevention-QmaVnIJYaI/index.html)
  * [AI Weekly: CDPA bill shows progress on coronavirus-tracking data privacy, but there’s still a ways to go](https://venturebeat.com/2020/05/08/ai-weekly-cdpa-bill-shows-progress-on-coronavirus-tracking-data-privacy-but-theres-still-a-ways-to-go/)
  * [Vivace’s AI Solution Offers Effective Early Warning System for COVID-19 Patients; Hospitals Offered Free Trial Amid Outbreak](https://www.aithority.com/machine-learning/vivaces-ai-solution-offers-effective-early-warning-system-for-covid-19-patients-hospitals-offered-free-trial-amid-outbreak/)
  * **[CT scan database of 1000 sets was created for teaching AI to diagnose COVID-19](https://www.eurekalert.org/pub_releases/2020-05/mrap-csd050820.php)** - MosMed.ai 
  * [COVID-19 Is Accelerating AI in Health Care. Are Federal Agencies Ready?](https://www.nextgov.com/ideas/2020/05/covid-19-accelerating-ai-health-care-are-federal-agencies-ready/165159/)
  * [France is using AI to check whether people are wearing masks on public transport](https://www.theverge.com/2020/5/7/21250357/france-masks-public-transport-mandatory-ai-surveillance-camera-software)
  * [Combating COVID-19: Telangana Police set to roll out AI-based system to track those not wearing masks at public places](https://www.aninews.in/news/national/general-news/combating-covid-19-telangana-police-set-to-roll-out-ai-based-system-to-track-those-not-wearing-masks-at-public-places20200509170302/)
  * [Imaginea Launches a Digital Framework to Battle COVID-19 at the Workplace](https://www.aithority.com/technology/analytics/imaginea-launches-a-digital-framework-to-battle-covid-19-at-the-workplace/)
  * **[COVID Moonshot: Can AI Algorithms and Volunteer Chemists Design a Knockout Antiviral?](https://spectrum.ieee.org/the-human-os/artificial-intelligence/medical-ai/covid-moonshot-can-ai-algorithms-and-volunteer-chemists-design-a-knockout-antiviral)** by IEEE spectrum
  * **[How Well Can Algorithms Recognize Your Masked Face?](https://www.wired.com/story/algorithms-recognize-masked-face/)**
  * [AI models suggest that masks can ‘significantly’ reduce spread of coronavirus](https://venturebeat.com/2020/04/29/ai-models-suggest-that-masks-can-significantly-reduce-spread-of-coronavirus/)
  * [Unexpected Scientific Insights into COVID-19 From AI Machine Learning Tool](https://scitechdaily.com/unexpected-scientific-insights-into-covid-19-from-ai-machine-learning-tool/)
  * [AbCellera and Lilly Slash Antibody Selection Time for COVID-19 With AI/Machine Learning](https://www.biospace.com/article/abcellera-and-lilly-slash-antibody-selection-time-for-covid-19-with-ai-machine-learning/)
  * **[FDA’s support of AI in telemedicine](https://www.mobihealthnews.com/news/fda-s-support-ai-telemedicine)**
  * [AI researchers set sights on detecting COVID-19 in imaging results](https://www.aiin.healthcare/topics/medical-imaging/ai-covid-19-imaging-results-x-ray-ct-scan)
  * ['Novel cloud-based web interface detects COVID-19 from CT scans'](https://health.economictimes.indiatimes.com/news/medical-devices/novel-cloud-based-web-interface-detects-covid-19-from-ct-scans/75626551)
  * **[China promotes local AI pilot zones](http://www.xinhuanet.com/english/2020-05/09/c_139043630.htm)**
  
* May 6
  * **[Epitopes.world taps AI to predict COVID-19 vaccine success](https://venturebeat.com/2020/05/05/epitopes-world-taps-ai-to-predict-covid-19-vaccine-success/)**
  * [An AI Assist for Spotting COVID-19 in X Rays](https://physics.aps.org/articles/v13/73)
  * [Tackling COVID-19 requires better governance of AI and other frontier technologies – here’s why](https://www.weforum.org/agenda/2020/05/success-in-emerging-covid-19-crisis-requires-better-governance-of-ai-and-other-frontier-technologies-here-s-why/)
  * [How AI and data analytics do their part in the COVID-19 crisis](https://www.zmescience.com/science/ai-healthcare-analytics-covid-19-050532/)
  * [Gartner: Top five areas CIOs can use AI to combat COVID-19](https://itbrief.co.nz/story/gartner-top-five-areas-cios-can-use-ai-to-combat-covid-19) 
  * [X-ray database could be key to virus fight](http://www.chinadaily.com.cn/a/202004/28/WS5ea78633a310a8b2411522da.html)
  * [THIS SIMPLE AI COULD SPEED UP THE COVID-19 CURE](https://www.inverse.com/innovation/machine-learning-replication-crisis)
  * [AI Used to Identify Drugs to Help Improve COVID-19 Survival Rates](https://techround.co.uk/news/ai-identify-drugs-improve-covid-19-survival-rates/)
  * **[RECENTLY RELEASED DATASETS FOR RESEARCHERS TO FIGHT COVID-19](https://analyticsindiamag.com/recently-released-datasets-for-researchers-to-fight-covid-19/)**
  
* May 5
  * [The groundbreaking way to search lungs for signs of Covid-19](https://www.bbc.com/news/business-52483082)
  * [How Artificial Intelligence can help fight COVID-19](https://www.bbva.com/en/how-artificial-intelligence-can-help-fight-covid-19/)
  * [AI tool speeds up search for COVID-19 treatments and vaccines](https://medicalxpress.com/news/2020-05-ai-tool-covid-treatments-vaccines.html)
  * **[5 Areas Where AI Can Help Healthcare CIOs during COVID-19](https://www.cxotoday.com/news-analysis/5-areas-where-ai-can-help-healthcare-cios-during-covid-19/)**
  * **[COVID effect: Medical AI takes prominence in Asia Pacific](https://www.geospatialworld.net/blogs/covid-effect-medical-ai-takes-prominence-in-asia-pacific/)**
  * [Can AI provide 'nowcasts' for COVID-19 on chest x-rays?](https://www.auntminnie.com/index.aspx?sec=ser&sub=def&pag=dis&ItemID=128869)
  * [AI Can Analyze COVID-19 Lungs in 10 secs, Identify High-Risk Patients](https://www.techtimes.com/articles/249383/20200505/ai-can-analyze-covid-19-lungs-in-10-secs-identify-high-risk-patients.htm)
  * [Flexible Throat Sensor Powered by AI to Track COVID-19 Symptoms](https://www.medgadget.com/2020/05/flexible-throat-sensor-powered-by-ai-to-track-covid-19.html)
  * [AI Hub Singapore creates COVID-19 monitoring app](https://asia.businesschief.com/technology/1869/AI-Hub-Singapore-creates-COVID-19-monitoring-app)
  * [5 Conversational AI Companies Tackling COVID-19](https://readwrite.com/2020/05/01/5-conversational-ai-companies-tackling-covid-19/)
  * [CeADAR offers AI projects under free licence to speed up Covid-19 solutions](https://www.siliconrepublic.com/machines/ceadar-ai-projects-free-licence-covid-19-solutions)
  * [AI Software Gets Mixed Reviews for Tackling Coronavirus](https://www.wsj.com/articles/ai-software-gets-mixed-reviews-for-tackling-coronavirus-11588597013?mod=tech_lead_pos1)
  * [Peter Staar, IBM Scientist, COVID-19 Open Research Dataset – Interview Series](https://www.unite.ai/peter-staar-ibm-scientist-covid-19-open-research-dataset-interview-series/)
  * [Cities are especially vulnerable to COVID-19. These organizations are leading the urban response.](https://www.weforum.org/agenda/2020/05/cities-urbanization-urban-living-coronavirus-covid19-pandemic-design/)
  * [AI and fact-checking: How Facebook deals with misinformation amid COVID-19](https://technology.inquirer.net/99070/ai-and-fact-checking-how-facebook-deals-with-misinformation-amid-covid-19)
  * [Hackers have stolen Covid-19 medical data from a Beijing-based AI firm](https://technode.com/2020/04/28/hackers-have-stolen-covid-19-medical-data-from-a-beijing-based-ai-firm/)
  * [Introducing the AI Economist: Why Salesforce Researchers are Applying Machine Learning to Economics](https://www.salesforce.com/company/news-press/stories/2020/4/salesforce-ai-economist/)
  * [Algorithmic economics might help recovery from Covid-19](https://www.ft.com/content/87f3d396-8de1-11ea-9e12-0d4655dbd44f)
  * **[Power of AI has limits in fight against Covid-19, experts caution](https://www.thenational.ae/business/technology/power-of-ai-has-limits-in-fight-against-covid-19-experts-caution-1.1014214)**
  * **[An NLU-Powered Tool to Explore COVID-19 Scientific Literature](https://ai.googleblog.com/2020/05/an-nlu-powered-tool-to-explore-covid-19.html)** by Google AI blog
  * [Universal Basic Income in the Age of COVID-19](https://www.unite.ai/universal-basic-income-in-the-age-of-covid-19/)
  * **[How AI is fighting COVID-19: the companies using intelligent tech to find new drugs](https://pharmaphorum.com/views-analysis-digital/how-ai-is-fighting-covid-19-the-companies-using-intelligent-tech-to-find-new-drugs/)**
  * **[Scale AI funds 8 projects for $3.4M amid COVID-19 crisis](https://www.canadianmanufacturing.com/technology/scale-ai-funds-8-projects-to-help-canada-amid-covid-19-crisis-252730/)**
  * [Cloud-based Supercomputer Accelerates COVID-19 Drug Discovery](https://www.hpcwire.com/2020/05/05/cloud-based-supercomputer-accelerates-covid-19-drug-discovery/)
  * [Current Health and Mayo Clinic Collaborate Using AI Against COVID-19](https://www.engineering.com/DesignerEdge/DesignerEdgeArticles/ArticleID/20238/Current-Health-and-Mayo-Clinic-Collaborate-Using-AI-Against-COVID-19.aspx)
  * [An AI can simulate an economy millions of times to create fairer tax policy](https://www.technologyreview.com/2020/05/05/1001142/ai-reinforcement-learning-simulate-economy-fairer-tax-policy-income-inequality-recession-pandemic/)
  * [Singapore firm unveils AI-driven contact tracing to help curb COVID-19](https://backendnews.net/2020/05/05/singapore-firm-unveils-ai-driven-contact-tracing-to-help-curb-covid-19/)
  * [AI study launched to monitor cardiac safety of COVID-19 patients receiving hydroxychloroquine](https://cardiacrhythmnews.com/ai-study-launched-to-monitor-cardiac-safety-of-covid-19-patients-receiving-hydroxychloroquine/)
  * **[AI firm asks for COVID-19 x-rays to develop new machine learning model](https://www.med-technews.com/news/ai-firm-asks-for-covid-19-x-rays-to-develop-new-machine-lear/)**
  * [Medidata analysis shows COVID-19 impact on trials](https://www.outsourcing-pharma.com/Article/2020/05/05/Medidata-shows-COVID-19-impact-on-clinical-trials)
  * **[California prediction: AI-driven model tracks coronavirus infections, deaths](https://www.mercurynews.com/2020/05/04/california-prediction-artificial-intelligence-driven-model-tracks-coronavirus-infections-deaths/)**
  * [A.I. engineers should spend time training not just algorithms, but also the humans who use them](https://fortune.com/2020/05/05/a-i-engineers-should-spend-time-training-not-just-algorithms-but-also-the-humans-who-use-them/)
  * [Democrats counter Trump’s fake coronavirus news with AI that fought ISIS propaganda](https://thenextweb.com/neural/2020/05/04/democrats-counter-trumps-fake-coronavirus-news-with-ai-that-fought-isis-propaganda/)
  * **[Gartner Identifies Five Areas Where AI Can Improve Decision Making for Government and Healthcare CIOs During the Coronavirus Pandemic](https://prwire.com.au/pr/89522/gartner-identifies-five-areas-where-ai-can-improve-decision-making-for-government-and-healthcare-cios-during-the-coronavirus-pandemic)**
  * [Pandemic: How A.I. and WAN acceleration can help to find a cure](https://www.itproportal.com/features/pandemic-how-ai-and-wan-acceleration-can-help-to-find-a-cure/)
  
* May 3
  * [How Well Can Algorithms Recognize Your Masked Face?](https://www.wired.com/story/algorithms-recognize-masked-face/)
  * [Oxford University Spin-out Begins Search for 10,000 X-rays to Help Predict Outcome for COVID-19](https://www.itnonline.com/content/oxford-university-spin-out-begins-search-10000-x-rays-help-predict-outcome-covid-19)
  * [Researchers release data set to evaluate COVID-19 chatbots and search engine](https://venturebeat.com/2020/04/27/researchers-release-data-set-to-evaluate-covid-19-chatbots-and-search-engines/?fbclid=IwAR0C7QGH5WI0NYpiocJG8C5PzBNtOhRmhfcFn1LNCz07GFIUUR-VNmNgH3U)

* May 2
  * [How A.I. Steered Doctors Toward a Possible Coronavirus Treatment](https://www.nytimes.com/2020/04/30/technology/coronavirus-treatment-benevolentai-baricitinib.html)
  
* May 1
  * **[Fighting COVID-19 with Emerging Technologies](https://blogs.idc.com/2020/05/01/fighting-covid-19-with-emerging-technologies/)** by IDC
  * **[The AI and data solutions helping to fight the coronavirus](https://www.ericsson.com/en/blog/2020/4/ai-data-solutions-helping-fight-coronavirus)**
  * [How can AI and data science help to fight the coronavirus?](https://www.ericsson.com/en/blog/2020/4/ai-and-data-science-to-fight-coronavirus)
  * **[Is AI trustworthy enough to help us fight COVID-19?](https://www.weforum.org/agenda/2020/05/covid19-coronavirus-artificial-intelligence-ai-response/)**
  * [Covid-19 and the workforce: Critical workers, productivity, and the future of AI](https://www.technologyreview.com/2020/04/30/1000888/covid-19-and-the-workforce-critical-workers-productivity-and-the-future-of-ai/)
  * [How can AI help with the COVID-19 vaccine search?](https://towardsdatascience.com/how-can-ai-help-with-the-covid-19-vaccine-search-a68d40fc0cb0)
  * [Do I sound sick to you? Researchers are building AI that would diagnose COVID-19 by listening to people talk.](https://www.businessinsider.com/ai-labs-diagnose-covid-19-voice-listening-talk-2020-4)
  * [Global AI (Artificial Intelligence) initiatives to fight the Deadly Coronavirus
](https://www.mygreatlearning.com/blog/coronavirus-can-ai-be-useful-in-a-global-outbreak/)
  * [Accelerating vaccine research for COVID-19 with HPC and AI](https://insidehpc.com/2020/05/accelerating-vaccine-research-for-covid-19-with-hpc-and-ai/)
  * [Enlisting AI in the push to combat Covid-19](https://www.upstreamonline.com/focus/enlisting-ai-in-the-push-to-combat-covid-19/2-1-797246)
  * [Tapping AI to battle Covid-19](https://www.straitstimes.com/tech/tapping-ai-to-battle-covid-19)
  * [FDA-cleared AI-based medical triage tool goes free for customers to help busy radiology diagnostics departments](https://techcrunch.com/2020/04/30/fda-cleared-ai-based-medical-triage-tool-goes-free-to-help-busy-radiology-diagnostics-departments/)
  * [AI model predicts the coronavirus pandemic will end in December](https://thenextweb.com/neural/2020/04/29/ai-model-predicts-the-coronavirus-pandemic-will-end-in-december/)
  * [Why was top Google artificial intelligence expert at meeting of government's secretive Sage scientific advisers?](https://www.dailymail.co.uk/news/article-8274333/Top-Google-AI-expert-attended-Sage-meeting-Government-scientific-advisers-coronavirus.html)
  * [rug discovery might be the best use of AI to tackle the pandemic](https://thenextweb.com/neural/2020/05/01/drug-discovery-might-be-the-best-use-of-ai-to-tackle-the-pandemic/)
  * **[LEVERAGING AI TO HUNT FOR POTENTIAL TREATMENTS: A COVID-19 EXAMPLE](https://bioteam.net/2020/04/leveraging-ai-to-hunt-for-potential-treatments-a-covid-19-example/)**
  * [Microsoft CEO Satya Nadella: 10 Thoughts on the Post-COVID-19 World](https://cloudwars.co/microsoft/microsoft-ceo-satya-nadella-10-thoughts-on-the-post-covid-19-world/)
  * [Researchers Crack COVID-19 Genetic Signature Using AI, Identify Origin](https://scitechdaily.com/researchers-crack-covid-19-genetic-signature-using-ai-identify-origin/)
  * [Google’s medical AI was super accurate in a lab. Real life was a different story.](https://www.technologyreview.com/2020/04/27/1000658/google-medical-ai-accurate-lab-real-life-clinic-covid-diabetes-retina-disease/)
  * [AI Platform Aims To Accelerate Drug Development for COVID-19](https://www.technologynetworks.com/informatics/news/ai-platform-aims-to-accelerate-drug-development-for-covid-19-333999)
  * **[Open-Source AI-derived drug discovery data to help combat COVID-19](http://www.labnews.co.uk/article/2030549/open-source-ai-derived-drug-discovery-data-to-help-combat-covid-19)**
  * [Machine Learning Tool Could Provide Unexpected Scientific Insights into COVID-19](https://newscenter.lbl.gov/2020/04/28/machine-learning-tool-could-provide-unexpected-scientific-insights-into-covid-19/)
  * [France Launches Telephone Voice Assistant for Coronavirus Questionnaire](https://voicebot.ai/2020/04/28/france-launches-telephone-voice-assistant-for-coronavirus-questionnaire/)
  * [Coronavirus in context: Scite.ai tracks positive and negative citations for COVID-19 literature](https://www.nature.com/articles/d41586-020-01324-6)
  * [G-20 to Utilize AI for Coronavirus Drug Development](https://www.nippon.com/en/news/yjj2020043000963/)
  * **[Virtual 2020 G20 Digital Ministers Summit on COVID-19](https://www.oecd.org/about/secretary-general/virtual-2020-g20-digital-ministers-summit-on-covid19-april-2020.htm)**
  
* April 29
  * [Fighting Coronavirus With AI, Part 1: Improving Testing with Deep Learning and Computer Vision](https://blog.paperspace.com/fighting-corona-virus-with-ai-medical-imaging-testing/)
  * [Is A.I. better at diagnosing illnesses than doctors? Don’t believe all the hype](https://fortune.com/2020/04/22/coronavirus-test-diagnosis-ai-doctors-illnesses-covid-19-research-artificial-intelligence/)
  * [Artificial Intelligence Enables Rapid COVID-19 Lung Imaging Analysis – HospiMedica](https://mc.ai/artificial-intelligence-enables-rapid-covid-19-lung-imaging-analysis-hospimedica/)
  * [AI-based IVD rises to challenge of novel coronavirus](https://www.labpulse.com/index.aspx?sec=sup&sub=pth&pag=dis&ItemID=801043)
  
* April 27
  * [Microsoft technology chief explains how A.I. could someday help rural people get through a pandemic](https://www.cnbc.com/2020/04/26/microsoft-cto-ai-can-help-rural-people-ride-out-covid-19.html)
  * [Chinese ‘Frontline’ COVID-19 Research Firm Reported Hacked: Data Now On Dark Web](https://www.forbes.com/sites/zakdoffman/2020/04/26/chinese-covid-19-detection-firm-just-got-hacked-data-for-sale-on-dark-web-new-report/#3a2c190f5dec)
  * [After coronavirus, AI could be central to our new normal](https://venturebeat.com/2020/04/08/after-coronavirus-ai-could-be-central-to-our-new-normal/)
  * [Claims that AI detects coronavirus in X-rays aren’t convincing medical experts](https://thenextweb.com/neural/2020/03/31/claims-that-ai-detects-coronavirus-in-x-rays-arent-convincing-medical-experts/)
  * **[Open-source AI tool aims to help identify coronavirus infections](https://www.zdnet.com/article/open-source-ai-tool-aims-to-help-identify-coronavirus-infections/)**
  * [Coronavirus: The role of AI in the ‘war’ against epidemics and pandemics](https://www.computerweekly.com/feature/Coronavirus-the-role-of-AI-in-the-war-against-epidemics-and-pandemics)
  * [How AI is finding drugs to treat coronavirus](https://sifted.eu/articles/ai-coronavirus-drugs/)
  * [Potential new treatment for COVID-19 uncovered by BenevolentAI enters trials](https://techcrunch.com/2020/04/14/potential-new-treatment-for-covid-19-uncovered-by-benevolentai-enters-trials/)
  * [Is A.I. better at diagnosing illnesses than doctors? Don’t believe all the hype](https://fortune.com/2020/04/22/coronavirus-test-diagnosis-ai-doctors-illnesses-covid-19-research-artificial-intelligence/)
  * [Coronavirus crisis gives an opportunity for AI to shine](https://www.techrepublic.com/article/coronavirus-crisis-gives-an-opportunity-for-ai-to-shine/)
  
* April 25
  * [COVID-19 AI Challenge: How Are Lockdowns Affecting the Most Vulnerable?](https://spectrum.ieee.org/the-human-os/biomedical/ethics/covid19-ai-challenge-how-are-lockdowns-affecting-the-most-vulnerable) @ IEEE Spectrum 
  * **[HL7 International and Audacious Inquiry Collaborate to Support COVID-19 Response](https://www.heraldmailmedia.com/news/state/hl7-international-and-audacious-inquiry-collaborate-to-support-covid-19-response/article_613a86c7-febd-5f19-a553-e7d8776bae18.html)**
  * [Israel is using AI to flag high-risk covid-19 patients](https://www.technologyreview.com/2020/04/24/1000543/israel-ai-prediction-medical-testing-data-high-risk-covid-19-patients/)
  * [Upload your Chest X-Ray, check if you have COVID-19 in one second: Chennai college develops new AI-driven software](https://www.edexlive.com/news/2020/apr/24/upload-your-chest-x-ray-check-if-you-have-covid-19-in-one-second-chennai-college-develops-new-ai-d-11532.html)
  * [Hospitals are using AI to predict the decline of Covid-19 patients — before knowing it works](https://www.statnews.com/2020/04/24/coronavirus-hospitals-use-ai-to-predict-patient-decline-before-knowing-it-works/)
  * [Could COVID-19 Help Refine AI, Data Analytics in Healthcare?](
  https://healthitanalytics.com/features/could-covid-19-help-refine-ai-data-analytics-in-healthcare)
  * [False claim: COVID-19 stands for Certification of Vaccination Identification by Artificial Intelligence​](https://www.reuters.com/article/uk-factcheck-covid-name-abbreviation/false-claim-covid-19-stands-for-certification-of-vaccination-identification-by-artificial-intelligence-idUSKCN2262AS)
  * **[Using AI to Find Peptide Therapeutics for COVID-19](https://www.biospace.com/article/using-ai-to-find-peptide-therapeutics-for-covid-19/)**
  * [NEW RESEARCH CLAIMS THAT AI CAN ZERO IN ON COVID-19 SYMPTOMS](https://analyticsindiamag.com/new-research-claims-that-ai-can-zero-in-on-covid-19-symptoms/)
  * [ONE SUPERCOMPUTER’S HPC AND AI BATTLE AGAINST THE CORONAVIRUS](https://www.nextplatform.com/2020/04/24/one-supercomputers-hpc-and-ai-battle-against-the-coronavirus/)
  * [How it feels like to have Covid-19! AI analysis on 350+ Covid-19 survivors](https://www.northeasttoday.in/2020/04/24/how-it-feels-like-to-have-covid-19-ai-analysis-on-350-covid-19-survivors/)
  * **[HOW TECH GIANTS ARE ENHANCING THEIR CONVERSATIONAL AI PLATFORMS TO FIGHT COVID-19](https://analyticsindiamag.com/how-tech-giants-are-enhancing-their-conversational-ai-platforms-to-fight-covid-19/)**
  
* April 24
  * **[Mapping the landscape of artificial intelligence applications against COVID-19](https://www.unglobalpulse.org/2020/03/mapping-the-landscape-of-artificial-intelligence-applications-against-covid-19/)**
  * [Doctors are using AI to triage covid-19 patients. The tools may be here to stay](https://www.technologyreview.com/2020/04/23/1000410/ai-triage-covid-19-patients-health-care/)
  * [AI And Robots Are Saving Lives Amid COVID-19](https://www.intelligentliving.co/ai-robots-saving-lives-covid-19/)
  * [Vonage Enables AI Chatbot for Spanish Government to Provide Accurate, Updated COVID-19 Information](https://www.morningstar.com/news/pr-newswire/20200423ny86660/vonage-enables-ai-chatbot-for-spanish-government-to-provide-accurate-updated-covid-19-information)
  * [AI and big data won’t work miracles in the fight against coronavirus](https://techcrunch.com/2020/03/26/ai-and-big-data-wont-work-miracles-in-the-fight-against-coronavirus/)
  * [Putting AI to work against COVID-19](https://www.cambridgenetwork.co.uk/news/putting-ai-work-against-covid-19)
  * [Maccabi to deploy AI that identifies patients at risk of developing COVID-19 complications](https://venturebeat.com/2020/04/22/maccabi-to-deploy-ai-that-identifies-patients-at-risk-of-developing-covid-19-complications/)
  * **[The Surge of Sensationalist COVID-19 AI Research](https://www.news-medical.net/health/The-Surge-of-Sensationalist-COVID-19-AI-Research.aspx)**
  * [In Vitro Confirmation of COVID-19 Drug Candidates Done Using AI-based Screening Technology](https://www.hospimedica.com/covid-19/articles/294781919/in-vitro-confirmation-of-covid-19-drug-candidates-done-using-ai-based-screening-technology.html)
  * [Why advances in AI are vital in the fight against Covid-19](https://govinsider.asia/connected-gov/why-advances-in-ai-are-vital-in-the-fight-against-covid-19/)
  * [Ping An’s COVID-19 Smart Image Reading System speeds up diagnoses and treatment](https://www.mobihealthnews.com/news/asia-pacific/ping-s-covid-19-smart-image-reading-system-speeds-diagnoses-and-treatment)
  * [Bolton NHS partners with Qure.ai for monitoring of COVID-19 patients](https://www.mobihealthnews.com/news/bolton-nhs-partners-qureai-monitoring-covid-19-patients)
  * **[Software tools for mining COVID-19 research studies go viral among scientists](https://www.geekwire.com/2020/software-tools-mining-covid-19-research-studies-go-viral-among-scientists/)**
 
* April 22
  * [Diagnosing COVID-19 using AI-based medical image analyses](https://www.quantib.com/blog/diagnosing-covid-19-using-ai-based-medical-image-analyses)
  * [Artificial intelligence could aid in fight against COVID-19](https://newsstand.clemson.edu/artificial-intelligence-could-aid-in-fight-against-covid-19/)
  * [Governments must build trust in AI to fight COVID-19 – Here’s how they can do it](https://www.weforum.org/agenda/2020/04/governments-must-build-trust-in-ai-to-fight-covid-19-here-s-how-they-can-do-it/) by World Economic Forum
  * [Thirona unveils AI software for COVID-19 analysis](https://www.auntminnie.com/index.aspx?sec=ser&sub=def&pag=dis&ItemID=128778)
  * [COVID-19 and artificial intelligence: protecting health-care workers and curbing the spread](https://www.thelancet.com/journals/landig/article/PIIS2589-7500(20)30054-6/fulltext)
  * [Startups and tech players on the frontline against Covid-19 in Africa](https://www.geospatialworld.net/blogs/startups-covid-africa/)
  * [Needed to fight COVID-19: A program for data on social determinants of health](https://www.fedscoop.com/needed-fight-covid-19-program-data-social-determinants-health/)
  * [Healx trains AI to find Covid-19 combination therapies](https://www.cambridgeindependent.co.uk/business/healx-trains-ai-to-find-covid-19-combination-therapies-9106885/)
  * [COVID-19 and privacy: artificial intelligence and contact tracing in combatting the pandemic](https://www.mccarthy.ca/en/insights/blogs/techlex/covid-19-and-privacy-artificial-intelligence-and-contact-tracing-combatting-pandemic)
  * [AI indicates which symptoms might be leading indicators of COVID-19](https://venturebeat.com/2020/04/21/ai-indicates-which-symptoms-might-be-leading-indicators-of-covid-19/)
  * [IBM CEO: Coronavirus Pandemic Accelerating Shift To Hybrid Cloud, AI](https://www.crn.com/news/cloud/ibm-ceo-coronavirus-pandemic-accelerating-shift-to-hybrid-cloud-ai)
  * [Fascinating AI/ML fight against COVID-19](https://medium.com/@baijayanta.roy/fascinating-ai-ml-fight-against-covid-19-67d91afcbfee)
  * [Putting AI to work against COVID-19](https://www.phgfoundation.org/blog/Putting-AI-to-work-against-COVID-19)
  * [AI use cases in the enterprise undergoing rapid change](https://searchenterpriseai.techtarget.com/feature/AI-use-cases-in-the-enterprise-undergoing-rapid-change)
  * [This AI tool helps hospitals predict COVID-19 bed and ventilator demand](https://www.zdnet.com/article/this-ai-tool-helps-hospitals-predict-covid-19-bed-and-ventilator-demand/)
  * [AI VIVO identifies list of 31 drugs that show potential for Covid-19 treatment](https://www.cambridgeindependent.co.uk/business/ai-vivo-identifies-list-of-31-drugs-that-show-potential-for-covid-19-treatment-9107179/)
  * [COVID-19 Has Revealed Change To Be A Matter Of Mindset. What Could This Mean For AI In The Future?](https://www.forbes.com/sites/kasiaborowska/2020/04/21/covid-19-has-revealed-change-to-be-a-matter-of-mindset-what-could-this-mean-for-ai-in-the-future/#181ac3e86d63)
  * [RADLogics Expands Deployment of Its AI-Powered Solution to Support Chest Imaging for COVID-19 Patients](https://www.aithority.com/technology/life-sciences/radlogics-expands-deployment-of-its-ai-powered-solution-to-support-chest-imaging-for-covid-19-patients/)
  * [HAS AI FAILED US DURING THIS CRISIS?](https://analyticsindiamag.com/has-ai-failed-us-during-this-crisis/)
  * [Who will be the winners in a post-pandemic economy?](https://www.weforum.org/agenda/2020/04/post-pandemic-economy-favour-fastest-movers/)
  
* April 21
  * [CT is Awful for Diagnosing COVID-19](https://lukeoakdenrayner.wordpress.com/2020/03/23/ct-scanning-is-just-awful-for-diagnosing-covid-19/)
  * [Can AI diagnose COVID-19 on CT scans? Can humans?](https://thehealthcareblog.com/blog/2020/03/23/can-ai-diagnose-covid-19-on-ct-scans-can-humans/)
  * [OnScale Launches ‘Digital Twins’ of Lungs to Improve COVID-19 Patients Outcomes](https://hitconsultant.net/2020/04/15/onscale-launches-digital-twins-of-lungs-to-improve-covid-19-patients-outcomes/#.Xp6ROqszb5U)
  * [AI-Powered CT Imaging System Shown to Detect COVID-19](https://www.mddionline.com/ai-powered-ct-imaging-system-shown-detect-covid-19)
  * [Radiologists sharing CT scans, X-rays in global effort to prevent COVID-19 deaths](https://www.abc.net.au/news/2020-04-18/radiologists-doctors-sharing-ct-images-of-coronavirus/12155560) @ABC news
  * [Chest CT Scans Don’t Advance COVID-19 Detection in Areas with Low Infection](https://www.diagnosticimaging.com/covid-19/chest-ct-scans-dont-advance-covid-19-detection-areas-low-infection)
  * [Covid-19 testing issues could sink plans to re-open the country. Might CT scans help?](https://www.statnews.com/2020/04/16/ct-scans-alternative-to-inaccurate-coronavirus-tests/)
  * [AI-assisted screening for COVID-19 using CT images](https://www.microcontrollertips.com/ai-assisted-screening-covid-19-using-ct-images/)
  * [How to create a trustworthy COVID-19 tracking technology](https://www.weforum.org/agenda/2020/04/covid-19-coronavirus-tracking-technology/) @World Economic Forum
  * [Leveraging AI to Battle This Pandemic — And The Next One](https://hbr.org/2020/04/leveraging-ai-to-battle-this-pandemic-and-the-next-one) @ Harvard Business Review
  * [This COVID-19 app would listen to your cough and use AI to predict whether you have coronavirus](https://www.businessinsider.com/app-would-listen-cough-predict-coronavirus-2020-4)
  * [AI emerged as a key contributor in the fight against coronavirus](https://www.ejinsight.com/eji/article/id/2440239/20200421-AI-emerged-as-a-key-contributor-in-the-fight-against-coronavirus)
  * [The NHS is using AI to predict coronavirus ventilator and ICU demand](https://thenextweb.com/neural/2020/04/20/the-nhs-is-using-ai-to-predict-coronavirus-ventilator-and-icu-demand/)
  * [Chinese companies push AI, biometric thermal imaging tech for U.S. deployment amid COVID-19](https://www.biometricupdate.com/202004/chinese-companies-push-ai-biometric-thermal-imaging-tech-for-u-s-deployment-amid-covid-19)
  * [COVID-19 restart: This start-up offers AI to ensure social-distancing at retail outlets](https://www.cnbctv18.com/retail/covid-19-restart-this-start-up-offers-ai-to-ensure-social-distancing-at-retail-outlets-5737291.htm)
  * [Landing AI ‘Social Distancing Detector’ Monitors Workplaces](https://medium.com/syncedreview/landing-ai-social-distancing-detector-monitors-workplaces-8ad08f3a143f)
  
* April 20
  * [新一代信息技术为疫情防控攻坚、复工复产按下“快进键”](http://www.xinhuanet.com/tech/2020-03/05/c_1125667595.htm)
  * [国家卫生健康委员会办公厅关于加强信息化支撑新型冠状病毒感染的肺炎疫情防控工作的通知](http://www.beijing.gov.cn/zhengce/zhengcefagui/202002/t20200205_1625272.html)
  * [Cal State La Researchers Use Data Visualization, AI in Fight Against COVID-19](https://martechseries.com/analytics/data-visualization/cal-state-la-researchers-use-data-visualization-ai-fight-covid-19/)
  * [Using artificial intelligence against the spread of COVID-19](https://www.jdsupra.com/legalnews/using-artificial-intelligence-against-23213/)
  * [COVID-19 | Disruptive tech and SME innovation can boost the fight against the virus](https://www.moneycontrol.com/news/coronavirus/covid-19-disruptive-tech-and-sme-innovation-can-boost-the-fight-against-the-virus-5165341.html)
  * [The (Sober) State of Artificial Intelligence in the Fight Against COVID-19](https://medicalfuturist.com/the-sober-state-of-artificial-intelligence-in-the-fight-against-covid-19/)
  * [Using AI to cope in the coronavirus era](https://www.raconteur.net/technology/covid-19-ai-solutions)
  * [Assistive diagnostic AI tool to tackle COVID-19 in Malaysia](https://www.biospectrumasia.com/news/91/15811/assistive-diagnostic-ai-tool-to-tackle-covid-19-in-malaysia.html)
  * [IDC: Coronavirus To Accelerate Public Sector AI Spending](https://www.rtinsights.com/coronavirus-ai-spending/)
  * **[Remote monitoring of COVID-19 patients using AI device](https://www.news-medical.net/news/20200419/Remote-monitoring-of-COVID-19-patients-using-AI-device.aspx)**
  * [Coronavirus Trackers Try Out AI Tools as Eyes Turn to Reopening](https://www.wsj.com/articles/coronavirus-trackers-try-out-ai-tools-as-eyes-turn-to-reopening-11587294000)
  * [MIT’s AI-powered device lets doctors monitor coronavirus patients remotely](https://thenextweb.com/neural/2020/04/15/mits-ai-powered-device-lets-doctors-monitor-coronavirus-patients-remotely/)

* April 18
  * [Mind-blowing: How can AI fight against coronavirus in China?](https://www.youtube.com/watch?v=VhtjdGlAidU)
  * [30 Israeli medical innovations to fight coronavirus](https://www.israel21c.org/30-israeli-medical-tech-solutions-to-help-fight-coronavirus/)
  * [Researchers release data set of CT scans from coronavirus patients](https://venturebeat.com/2020/04/01/researchers-release-data-set-of-ct-scans-from-coronavirus-patients/)
  * [Tech companies are deploying AI to spot COVID-19, unburden overworked healthcare staff](https://www.healthimaging.com/topics/artificial-intelligence/tech-companies-ai-covid-19-unburden-healthcare)
  * [AI Uncovers a Potential Treatment for Covid-19 Patients](https://www.wired.com/story/ai-uncovers-potential-treatment-covid-19-patients/)
  * [AI checks CT scans for COVID-19](https://physicsworld.com/a/ai-checks-ct-scans-for-covid-19/)
  * [AI predicts COVID-19 treatments and vaccine will take between 2 to 5 years](http://english.hani.co.kr/arti/english_edition/e_international/937202.html)
  * [AI Can Help Hospitals Triage COVID-19 Patients](https://spectrum.ieee.org/the-human-os/artificial-intelligence/medical-ai/ai-can-help-hospitals-triage-covid19-patients)
  * [Don’t expect AI to solve the coronavirus crisis on its own](https://www.vox.com/recode/2020/4/13/21214948/coronavirus-covid-cure-treatment-artificial-intelligence)
  * [Some countries in the Middle East are using artificial intelligence to fight the coronavirus pandemic](https://www.cnbc.com/2020/04/16/countries-in-the-middle-east-are-using-ai-to-fight-coronavirus.html)
  * [AI v Covid-19 - idsia](http://people.idsia.ch/~juergen/ai-covid.html)
  * [Covid-19 Crisis Illustrates Need for Solid AI/ML Strategy](https://www.forbes.com/sites/forbesinsights/2020/04/15/covid-19-crisis-illustrates-need-for-solid-aiml-strategy/#4ba9ddc8151d)
  * [Why Covid-19 only accelerates South Korea’s AI ambitions](https://www.lowyinstitute.org/the-interpreter/why-covid-19-only-accelerates-south-korea-s-ai-ambitions)
  * [AI-powered solutions play major role in virus fight](https://en.yna.co.kr/view/AEN20200409007500320)
  * [Coronavirus: AI steps up in battle against Covid-19](https://www.bbc.com/news/technology-52120747)
  * [COVID-19 will accelerate AI's replacement of humans as factor of production](https://thehill.com/opinion/technology/492492-covid-19-will-accelerate-ais-replacement-of-humans-as-factor-of-production)
  * [Potential treatment for COVID-19 identified by BenevolentAI using artificial intelligence enters randomised clinical trial](https://benevolent.ai/news/potential-treatment-for-covid-19-identified-by-benevolentai-using-artificial-intelligence-enters-clinical-testing)
  * [COVID-19 Pandemic Impact: Global R&D Spend For AI in Healthcare and Pharmaceuticals Will Increase US$1.5 Billion By 2025](https://www.abiresearch.com/press/covid-19-pandemic-impact-global-rd-spend-ai-healthcare-and-pharmaceuticals-will-increase-us15-billion-2025/)
  * [On Guard Against COVID-19: AI Projects That Deserve a Shout-Out](https://hackernoon.com/on-guard-against-covid-19-ai-projects-that-deserve-a-shout-out-3p1m3ykk)
  * [AI Becomes An Ally In The Fight Against COVID-19](https://www.forbes.com/sites/servicenow/2020/04/17/ai-becomes-an-ally-in-the-fight-against-covid-19/#4d8f14803f5f)
  * [AI Gets Into The Fight With COVID-19](https://www.forbes.com/sites/gilpress/2020/04/17/ai-gets-into-the-fight-with-covid-19/#9df6d2c20c04)
  * [COVID-19 might accelerate or change previous AI adoption strategies](https://www.atlanticcouncil.org/blogs/geotech-cues/covid-19-might-accelerate-or-change-previous-ai-adoption-strategies/)
  * **[Fifth edition of the AI Breakfast: "Covid-19: Myths and realities of tracking applications"](https://www.coe.int/en/web/artificial-intelligence/-/ai-breakfasts-5th-edition-covid-19-myths-and-realities-of-tracking-applications-)**
  * [How AI helps scientists find reliable coronavirus research](https://thenextweb.com/neural/2020/04/14/how-ai-helps-scientists-find-reliable-coronavirus-research/)
  * [Why artificial intelligence is so important in the coronavirus era](https://fortune.com/2020/04/14/artificial-intelligence-coronavirus-health-medicine/)
  * [A clinical team used MIT CSAIL’s AI to remotely monitor a COVID-19 patient](https://venturebeat.com/2020/04/14/a-clinical-team-used-mit-csails-ai-to-remotely-monitor-a-covid-19-patient/)
  * [Human and AI annotations aim to improve scholarly results in COVID-19 searches](https://news.psu.edu/story/616031/2020/04/17/research/human-and-ai-annotations-aim-improve-scholarly-results-covid-19)
  * [Chinese startup Rokid pitches COVID-19 detection glasses in US](https://techcrunch.com/2020/04/16/chinese-startup-rokid-pitches-covid-19-detection-glasses-in-u-s)
  * [OSTP, NIST Launch AI Program for Coronavirus Research](https://www.meritalk.com/articles/ostp-nist-launch-ai-program-for-coronavirus-research/)
  * [Tunisia researchers use AI, X-rays to create online virus scan tool](https://www.dispatchlive.co.za/news/africa/2020-04-17-tunisia-researchers-use-ai-x-rays-to-create-online-virus-scan-tool/)
  * [Fei-Fei Li Proposes AI-Assisted Elder Care Solution at Stanford-Hosted Virtual Conference on COVID‑19 and AI](https://syncedreview.com/2020/04/01/fei-fei-li-proposes-ai-assisted-elder-care-solution-at-stanford-hosted-virtual-conference-on-covid%E2%80%9119-and-ai/)

* April 12
  * [HOW HOSPITALS CAN TAP AI TO MANAGE STAFF BETTER AMID COVID-19 CRISIS](https://analyticsindiamag.com/how-hospitals-can-tap-ai-to-manage-staff-better-amid-covid-19-crisis/)
  * [THIS SMART RING USES AI TO SPOT COVID-19 — BEFORE SYMPTOMS BEGIN](https://futurism.com/neoscope/smart-ring-ai-spot-covid19-before-symptoms-begin)
  * [AI CT Scan Analysis for COVID-19 Detection and Patient Monitoring](https://syncedreview.com/2020/03/18/ai-ct-scan-analysis-for-covid-19-detection-and-patient-monitoring/)
  
* April 11
  * [4 Ways AI Is Making the World a Safer Place](https://www.entrepreneur.com/article/348909)
  * [AI Weekly: The sudden speed of technological change in a coronavirus world](https://venturebeat.com/2020/04/10/ai-weekly-the-sudden-speed-of-technological-change-in-a-coronavirus-world/)
  * [COVID-19 Datasets Bring AI Experts, Life Sciences Researchers Together For A Cure](http://www.bio-itworld.com/2020/04/10/covid-19-datasets-bring-ai-experts-life-sciences-researchers-together-for-a-cure.aspx)
  * [Tracking COVID-19: Hunting the Virus with Technology, AI, and Analytics](https://hai.stanford.edu/news/tracking-covid-19-hunting-virus-technology-ai-and-analytics)
  * [Using AI to analyze coronavirus data](https://federalnewsnetwork.com/artificial-intelligence/2020/04/using-ai-to-analyze-coronavirus-data/)
  * [Digital Transformation For Good Shines As We Fight COVID-19](https://www.forbes.com/sites/danielnewman/2020/04/10/digital-transformation-for-good-shines-as-we-fight-covid-19/#399d21ab4946)
  * [COVID-19: Emerging technologies are now critical infrastructure – what that means for governance](https://www.weforum.org/agenda/2020/04/covid-19-emerging-technologies-are-now-critical-infrastructure-what-that-means-for-governance/)
  * [AI Algorithm-Based Test Can Speed Up COVID-19 Testing Eightfold and Locate Asymptomatic Carriers](https://www.hospimedica.com/covid-19/articles/294781552/ai-algorithm-based-test-can-speed-up-covid-19-testing-eightfold-and-locate-asymptomatic-carriers.html)

* April 10
  * [How Alibaba DAMO Academy AI System Detects Coronavirus Cases](https://www.alibabacloud.com/blog/how-alibaba-damo-academy-ai-system-detects-coronavirus-cases_595979)
  * [AI and the coronavirus fight: How artificial intelligence is taking on COVID-19](https://www.zdnet.com/article/ai-and-the-coronavirus-fight-how-artificial-intelligence-is-taking-on-covid-19/)
  * [GSK, Vir Use CRISPR, Artificial Intelligence to Find COVID-19 Cure](https://pharmanewsintel.com/news/gsk-vir-use-crispr-artificial-intelligence-to-find-covid-19-cure)
  * [Fight Coronavirus [COVID-19](https://www.alibabacloud.com/campaign/fight-coronavirus-covid-19) by Alibaba cloud
  * [Global AI (Artificial Intelligence) Initiatives to Fight the Deadly Coronavirus](https://www.mygreatlearning.com/blog/coronavirus-can-ai-be-useful-in-a-global-outbreak/)
  * [Open data, data use, and COVID-19](https://opendatawatch.com/what-is-being-said/data-in-the-time-of-covid-19/)
  * [Hospitals scramble to enlist AI in fight against pandemic](https://www.healthcareitnews.com/ai-powered-healthcare/hospitals-scramble-enlist-ai-fight-against-pandemic)
  * [Biofourmis’ AI-Powered Tech Being Used in Remote Monitoring of COVID-19 Patients in Hong Kong](https://www.wearable-technologies.com/2020/03/biofourmis-ai-powered-tech-being-used-in-remote-monitoring-of-covid-19-patients-in-hong-kong/)
  * [Care Mentor AI develops Artificial Intelligence for rapid diagnosis of COVID-19](https://www.itnonline.com/content/care-mentor-ai-develops-artificial-intelligence-rapid-diagnosis-covid-19)
  * [Real Use for AI Tools During COVID-19: Part Two](https://www.diagnosticimaging.com/ct/real-use-ai-tools-during-covid-19-part-two)
  * [Microsoft dedicates $20M from AI for Health program to COVID-19 data analysis](https://www.geekwire.com/2020/microsoft-dedicates-20m-ai-health-program-coronavirus-data-analysis/)
  * [Ai used to detect COVID-19 pneumonia](https://www.news-medical.net/news/20200409/Ai-used-to-detect-COVID-19-pneumonia.aspx)
  * [AI and cloud computing used to develop COVID-19 vaccine](https://www.drugtargetreview.com/news/59650/ai-and-cloud-computing-used-to-develop-covid-19-vaccine/)
  * [Coughvid app uses AI to detect COVID-19 from coughing sounds](https://www.slashgear.com/coughvid-app-uses-ai-to-detect-covid-19-from-coughing-sounds-10616214/)
  * **[A neural network can help spot Covid-19 in chest x-rays](https://www.technologyreview.com/2020/03/24/950356/coronavirus-neural-network-can-help-spot-covid-19-in-chest-x-ray-pneumonia/)**
  * [Spending in Artificial Intelligence to accelerate across the public sector due to automation and social distancing compliance needs in response to COVID-19, says IDC](https://www.telecomtv.com/content/ai-ml/spending-in-artificial-intelligence-to-accelerate-across-the-public-sector-due-to-automation-and-social-distancing-compliance-needs-in-response-to-covid-19-says-idc-38318/)
  * [Huawei helps Health Ministry fight Covid-19 with tech solutions](https://www.thestar.com.my/news/nation/2020/04/10/huawei-helps-health-ministry-fight-covid-19-with-tech-solutions)

* April 9
  * [Hospitals Deploy AI Tools to Detect COVID-19 on Chest Scans](https://spectrum.ieee.org/the-human-os/biomedical/imaging/hospitals-deploy-ai-tools-detect-covid19-chest-scans)
  * [Software and Genetic Sequencing Track the Coronavirus's Path](https://spectrum.ieee.org/the-human-os/biomedical/devices/genetic-sequencing-and-online-software-tools-track-caronaviruss-path)
  * [Halting COVID-19: The Benefits and Risks of Digital Contact Tracing](https://spectrum.ieee.org/the-human-os/biomedical/ethics/halting-covid19-benefits-risks-digital-contact-tracing)
  * [Responding to COVID-19 with AI and machine learning](https://www.id-hub.com/2020/04/08/responding-to-covid-19-with-ai-and-machine-learning/)
  * [AI APP, PART-FUNDED BY EU, COLLECTS THE SOUNDS OF COVID-19](https://erc.europa.eu/news/ai-app-part-funded-eu-collects-sounds-covid-19)
  * [How AI Is Helping in the Fight Against COVID-19](https://medium.com/pcmag-access/how-ai-is-helping-in-the-fight-against-covid-19-e4c19e0f8ff)
  * [How AI is helping scientists in the fight against COVID-19, from robots to predicting the future](https://www.geekwire.com/2020/ai-helping-scientists-fight-covid-19-robots-predicting-future/)
  * [Coronavirus: Covid-19 detecting apps face teething problems](https://www.bbc.com/news/technology-52215290) on BBC
  * [How AI And Data Science Are Helping To Understand And Tackle COVID-19](https://www.forbes.com/sites/victoriacollins/2020/04/08/how-ai-and-data-science-are-helping-to-understand-and-tackle-covid-19/#27cfa7377c84)
  * [Darren Schulte, MD: Leveraging AI During the COVID-19 Pandemic](https://www.mdmag.com/medical-news/darren-schulte-md-leveraging-ai-during-covid-19)
  * [Microsoft exec says coronavirus could spark big shift for AI in health care](https://www.seattletimes.com/business/microsoft-exec-says-coronavirus-could-spark-big-shift-for-ai-in-health-care/)
  * [Artificial Intelligence Platform Helps Find Combination Drug Treatments for COVID-19](https://www.hospimedica.com/covid-19/articles/294781616/artificial-intelligence-platform-helps-find-combination-drug-treatments-for-covid-19.html)
  * [How next-generation information technologies tackled COVID-19 in China](https://www.weforum.org/agenda/2020/04/how-next-generation-information-technologies-tackled-covid-19-in-china/) on World Economic Forum
  * [Helping contact centers respond rapidly to customer concerns about COVID-19](https://cloud.google.com/blog/products/ai-machine-learning/support-for-contact-centers-during-covid-19)
  * [AI tool predicts severe respiratory illness in early COVID-19](https://www.hospitalhealth.com.au/content/clinical-services/news/ai-tool-predicts-severe-respiratory-illness-in-early-covid-19-490891681#axzz6J4QPkkm8)
  * [Combating Covid-19: How voice AI apps can be a lifesaver today](https://www.financialexpress.com/industry/technology/combating-covid-19-how-voice-ai-apps-can-be-a-lifesaver-today/1923006/)
  * [IBM shares AI tools to better understand and treat COVID-19](https://www.engadget.com/ibm-coronavirus-ai-research-tools-162123059.html)

* April 7
  * [Tech firms mobilize AI capabilities to fight COVID-19](http://m.theinvestor.co.kr/view.php?ud=20200406000881)
  * [COVID-19: How Korea is using innovative technology and AI to flatten the curve](https://news.itu.int/covid-19-how-korea-is-using-innovative-technology-and-ai-to-flatten-the-curve/)
  * [Vendors debut AI X-ray system for COVID-19, give it away for free](https://www.healthcareitnews.com/news/vendors-debut-ai-x-ray-system-covid-19-give-it-away-free)
  * [THE AI INDUSTRY RESPONSES TO COVID-19](https://medium.com/@arstudioz11/the-ai-industry-responses-to-covid-19-dee4081c1dc2)
  * [Overview of AI Applications Assisting Us In The Fight Against Covid-19](https://hackernoon.com/overview-of-ai-applications-assisting-us-in-the-fight-against-covid-19-9y743yy2)
  * [HEALTHCARE CENTERS ARE TURNING TO AI TO COMBAT COVID-19](https://www.analyticsinsight.net/healthcare-centers-turning-ai-combat-covid-19/)
  * [COVID-19 precaution: Dubai Police using AI to find out if your trip was essential](https://gulfnews.com/uae/covid-19-precaution-dubai-police-using-ai-to-find-out-if-your-trip-was-essential-1.70829268)
  * [Microsoft Offers COVID-19 Chatbot to Help Healthcare Providers Triage Patients](https://voicebot.ai/2020/03/23/microsoft-offers-covid-19-chatbot-to-help-healthcare-providers-triage-patients/)
  * [New AI Technology Partnership To Fight COVID-19](https://blog.singularitynet.io/new-ai-technology-partnership-to-fight-covid-19-37c356d2ea0c)
  * [AI is helping scientists navigate thousands of COVID-19 research papers](https://bdtechtalks.com/2020/04/06/ai-coronavirus-research-papers-cord-19/)
  * [Russia: AI and hi-tech surveillance to fight the Covid-19 epidemic amidst fears of rights violations](https://observatoryihr.org/news/russia-ai-and-hi-tech-surveillance-to-fight-the-covid-19-epidemic-amidst-fears-of-rights-violations/)
  * [Healx to use AI platform Healnet to find COVID-19 treatments](https://www.information-age.com/healx-use-ai-platform-healnet-find-covid-19-treatments-123488827/)
  * [Using AI to Speed Up COVID-19 Diagnosis](https://www.technologynetworks.com/informatics/product-news/using-ai-to-speed-up-covid-19-diagnosis-333075)
  * [Europe seeks to harness power of AI in COVID-19 crisis](https://physicsworld.com/a/europe-seeks-to-harness-power-of-ai-in-covid-19-crisis/)
  * [OpenMed Launches First-Ever AI COVID-19 Triage To Coordinated Testing Platform](https://www.prnewswire.com/news-releases/openmed-launches-first-ever-ai-covid-19-triage-to-coordinated-testing-platform-301035579.html)
  * [NVIDIA Adds GPU and AI Expertise to COVID-19 HPC Consortium](https://insidehpc.com/2020/04/nvidia-adds-gpu-and-ai-expertise-to-covid-19-hpc-consortium/)
  * [Acko General launches AI-based Covid-19 symptom checker](https://yourstory.com/2020/04/acko-general-ai-based-covid-19-symptom-checker)
  * **[Stanford researchers propose AI in-home system that can monitor for coronavirus symptoms](https://venturebeat.com/2020/04/06/stanford-researchers-propose-ai-in-home-system-that-can-monitor-for-coronavirus-symptoms/)**
  * [AI runs smack up against a big data problem in COVID-19 diagnosis](https://www.zdnet.com/article/ai-runs-smack-up-against-a-big-data-problem-in-covid-19-diagnosis/)
  * [Oxford firm to screen 15,000 drugs in search for coronavirus cure](https://www.theguardian.com/business/2020/mar/31/oxford-firm-to-screen-15000-drugs-in-search-for-coronavirus-treatment)
  * [Seoul city utilizes AI calling system to monitor people in COVID-19 self-quarantine](http://english.seoul.go.kr/seoul-city-utilizes-ai-calling-system-to-monitor-people-in-covid-19-self-quarantine/)
  * [MIT Researchers Turn COVID-19 into a Classical Melody Using AI](https://interestingengineering.com/mit-researchers-turn-covid-19-into-a-classical-melody-using-ai)
  * [Chatbots provide millions with COVID-19 information every day, but they can be improved - here’s how](https://www.weforum.org/agenda/2020/04/chatbots-covid-19-governance-improved-here-s-how/)

* April 5
  * [TOP HACKATHONS DEDICATED TO FIGHT COVID-19](https://analyticsindiamag.com/top-hackathons-dedicated-to-fight-covid-19/)
  * [Coronavirus: seven ways collective intelligence is tackling the pandemic](http://theconversation.com/coronavirus-seven-ways-collective-intelligence-is-tackling-the-pandemic-133553)

* April 4
  * [Technology key to COVID-19 battle](http://www.chinadailyhk.com/article/126622)
  * [At Stanford’s AI Conference, Harnessing Tech to Fight COVID-19](https://www.extremetech.com/extreme/308714-at-stanfords-ai-conference-harnessing-tech-to-fight-covid-19)
  * [HELP with COVID](https://helpwithcovid.com/)
  * [Detecting COVID-19 in X-ray images with Keras, TensorFlow, and Deep Learning](https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/)
  * [Coronavirus Reveals Limits of AI Health Tools](https://www.wsj.com/articles/coronavirus-reveals-limits-of-ai-health-tools-11582981201)
  * [Artificial Intelligence against COVID-19: An Early Review](https://towardsdatascience.com/artificial-intelligence-against-covid-19-an-early-review-92a8360edaba)
  * [AI technology to screen existing drugs for use against COVID-19](https://www.drugtargetreview.com/news/59188/ai-technology-to-screen-existing-drugs-for-use-against-covid-19/)
  * [AI Update: Using Artificial Intelligence to Combat COVID-19](https://www.covingtondigitalhealth.com/2020/04/ai-update-using-artificial-intelligence-to-combat-covid-19/)
  * [Analysis: Applying AI in the Fight Against The Coronavirus](https://hitconsultant.net/2020/04/01/analysis-applying-ai-in-the-fight-against-the-coronavirus/#.Xofeaogzb-h)
  * [Vuno offers free AI solution for reading COVID-19 lung images](http://www.koreabiomed.com/news/articleView.html?idxno=7919)
  * [Using Artificial Intelligence to detect COVID-19](https://becominghuman.ai/using-artificial-intelligence-to-detect-covid-19-6fcd9857b93f)
  * [How Hospitals Are Using AI to Battle Covid-19](https://hbr.org/2020/04/how-hospitals-are-using-ai-to-battle-covid-19)
  * [Covid-19: Focus on what China did right, not wrong](https://asiatimes.com/2020/04/covid-19-focus-on-what-china-did-right-not-wrong/)
  * [Tech News: Data and Artificial Intelligence in the Covid-19 crisis](https://www.iol.co.za/business-report/tech-news-data-and-artificial-intelligence-in-the-covid-19-crisis-45991847)
  * [Collaboration Aims to Fast-track AI Solution for Rapid COVID-19 Diagnosis Using Chest X-rays](https://thejournalofmhealth.com/collaboration-aims-to-fast-track-ai-solution-for-rapid-covid-19-diagnosis-using-chest-x-rays/)
  * [Big tech’s covid-19 opportunity](https://www.economist.com/leaders/2020/04/03/big-techs-covid-19-opportunity)
  * [Lawrence Livermore Lab Uses Artificial Intelligence and Supercomputers in Global Fight Against COVID-19](https://scitechdaily.com/lawrence-livermore-lab-uses-artificial-intelligence-and-supercomputers-in-global-fight-against-covid-19/)
  * [BenevolentAI analyses approved drug as potential Covid-19 treatment](https://www.cambridgeindependent.co.uk/business/benevolentai-analyses-approved-drug-as-potential-covid-19-treatment-9102147/)
  * [AI project aims to diagnose COVID-19 using voice analysis](https://artificialintelligence-news.com/2020/04/01/ai-project-diagnose-covid-19-voice-analysis/)
  * [‘Human experts will make the call’: Stanford launches an accelerated test of AI to help care for Covid-19 patients](https://www.statnews.com/2020/04/01/stanford-artificial-intelligence-coronavirus/)
  * [COVID-19 machine learning effort: Preprints are key](https://www.cshl.edu/covid-19-machine-learning-effort-preprints-are-key/)
  * [How Medical Imaging Datasets Can Help AI to Diagnosis the Covid-19 Like Deadly Virus?](https://www.cogitotech.com/blog/how-medical-imaging-datasets-can-help-ai-to-diagnosis-covid-19-virus/)
  * [AI played a part in spotting COVID-19. Now, it’s helping to fight it](https://kainos.com/ai-played-a-part-in-spotting-covid-19-now-its-helping-to-fight-it)
  * [Online pandemic tracker launched to flag surges in COVID-19 cases](https://www.thestar.com/news/gta/2020/04/02/online-pandemic-tracker-launched-to-flag-surges-in-covid-19-cases.html)

* April 3
  * [Using AI responsibly to fight the coronavirus pandemic](https://techcrunch.com/2020/04/02/using-ai-responsibly-to-fight-the-coronavirus-pandemic/)
  * [STAT’s guide to how hospitals are using AI to fight Covid-19](https://www.statnews.com/2020/03/31/hospitals-artificial-intelligence-coronavirus/)
  * [UNLOCKING POTENTIALS OF NLP TO FIGHT AGAINST COVID-19 CRISIS](https://www.analyticsinsight.net/unlocking-potentials-nlp-fight-covid-19-crisis/)
  * [COVID-19: Artificial Intelligence joins the fight against Coronavirus](https://www.facebook.com/watch/?v=774609909730484)
  * [How AI could help in the fight against COVID-19](https://www.techrepublic.com/article/how-ai-could-help-in-the-fight-against-covid-19/)
  * [How is AI being used in the fight against COVID19?](https://www.analyticssteps.com/blogs/how-ai-being-used-fight-against-covid19)
  * [11 WAYS AI IS FIGHTING CORONAVIRUS OUTBREAK](https://analyticsindiamag.com/ai-corona-covid19-fight-deepmind-alibaba-baidu-algorithm/)
  * [Initiative Seeks to Leverage Artificial Intelligence to Defeat COVID-19](https://www.computer.org/publications/tech-news/research/initiative-to-defeat-covid-19-thanks-to-artificial-intelligence) by IEEE Computer Society
  * [AI vs COVID-19: Here are the AI tools and services fighting coronavirus](https://artificialintelligence-news.com/2020/03/23/ai-vs-covid-19-here-are-the-ai-tools-and-services-fighting-coronavirus/)
  * [Insights on Artificial intelligence Studies on COVID-19](https://www.techiexpert.com/insights-on-artificial-intelligence-studies-on-covid-19/)
  * [An artificial intelligence-based first-line defence against COVID-19: digitally screening citizens for risks via a chatbot](https://www.biorxiv.org/content/10.1101/2020.03.25.008805v2.full)

* [Awesome Coronavirus - Useful projects and resources for COVID-19 (2019 novel Coronavirus)](https://github.com/soroushchehresa/awesome-coronavirus)
* [Artificial Intelligence against COVID-19](https://www.revelis.eu/en/artificial-intelligence-against-covid19/)
* [COVID-19 + Imaging AI Resources](https://aimi.stanford.edu/resources/covid19) by Center for Artificial Intelligence in Medicine & Imaging, Standford Univ. 
* [List of COVID-19 Resources for Machine Learning and Data Science](https://www.marktechpost.com/2020/04/12/list-of-covid-19-resources-for-machine-learning-and-data-science-research/)
* [Coronavirus: Research, Commentary, and News](https://www.sciencemag.org/coronavirus-research-commentary-and-news?intcmp=ghd_cov) by Science
* [Itonline COVID-19 channel](https://www.itnonline.com/channel/coronavirus-covid-19)
* [Latest Coronavirus Updates for the Healthcare Community](https://patientengagementhit.com/news/latest-coronavirus-updates-for-the-healthcare-communit)
* [Experimental AI tool predicts which COVID-19 patients develop respiratory disease](https://www.sciencedaily.com/releases/2020/03/200330152135.htm)
* [World Economy Forum - AI can help with the COVID-19 crisis - but the right human input is key](https://www.weforum.org/agenda/2020/03/covid-19-crisis-artificial-intelligence-creativity/)
* [AI Can Help Scientists Find a Covid-19 Vaccine](https://www.wired.com/story/opinion-ai-can-help-find-scientists-find-a-covid-19-vaccine/)
* [Latest Coronavirus Updates for the Healthcare Community](https://patientengagementhit.com/news/latest-coronavirus-updates-for-the-healthcare-community)
* [Leveraging AI for COVID-19 Outreach, Population Health Management](https://healthitanalytics.com/news/leveraging-ai-for-covid-19-outreach-population-health-management)
* [Amazon Pledges $20M to Support COVID-19 Diagnostics, Research](https://healthitanalytics.com/news/amazon-pledges-20m-to-support-covid-19-diagnostics-research)
* [White House Urges AI Experts to Develop Tools for COVID-19 Dataset](https://healthitanalytics.com/news/white-house-urges-ai-experts-to-develop-tools-for-covid-19-dataset)
* [Is Artificial Intelligence Mature Enough to Combat COVID-19?](https://healthitanalytics.com/news/is-artificial-intelligence-mature-enough-to-combat-covid-19)
* [Artificial intelligence in the fight against COVID-19](https://www.bruegel.org/2020/03/artificial-intelligence-in-the-fight-against-covid-19/)
* [How Artificial Intelligence Is Helping Fight The COVID-19 Pandemic](https://www.entrepreneur.com/article/348368)
* [AI (Artificial Intelligence) Companies That Are Combating The COVID-19 Pandemic](https://www.forbes.com/sites/tomtaulli/2020/03/28/ai-artificial-intelligence-companies-that-are-combating-the-covid-19-pandemic/#4f32d96058f8)
* [UN, WHO & Mila Map the AI vs COVID-19 Battlefield](https://syncedreview.com/2020/03/27/un-who-mila-map-the-ai-vs-covid-19-battlefield/)
* [Fighting Covid-19 Using Data Science, AI, and Machine Learning](https://intellipaat.com/blog/fighting-covid-19-using-data-science-ai-and-machine-learning/)
* [A.I. Versus the Coronavirus](https://www.nytimes.com/2020/03/26/science/ai-versus-the-coronavirus.html)
* [Hospitals Deploy AI Tools to Detect COVID-19 on Chest Scans](https://spectrum.ieee.org/the-human-os/biomedical/imaging/hospitals-deploy-ai-tools-detect-covid19-chest-scans)
* [5 Ways Data Scientists Can Help Respond to COVID-19 and 5 Actions to Avoid](https://towardsdatascience.com/5-ways-data-scientists-can-help-respond-to-covid-19-and-5-actions-to-avoid-d2accab283d1)
* [Dutch companies Offer Free Innovative COVID-19 AI Software](https://www.itnonline.com/content/dutch-companies-offer-free-innovative-covid-19-ai-software)
* [New York State Announces COVID-19 Technology SWAT Team](https://www.programmableweb.com/news/new-york-state-announces-covid-19-technology-swat-team/brief/2020/03/30)
* [Daily API RoundUp: COVID-19, TeamWave, DroneDeploy, Canada Post](https://www.programmableweb.com/news/daily-api-roundup-covid-19-teamwave-dronedeploy-canada-post/brief/2020/04/01)
* [How AI Is Helping Us With The Coronavirus Pandemic](https://medium.com/reality-engines/how-ai-is-helping-us-with-the-coronavirus-pandemic-d3c555209323)
* [COVID-Net: an open source neural network for COVID-19 detection](https://medium.com/@sheldon.fernandez/covid-net-an-open-source-neural-network-for-covid-19-detection-48b8a55e6d44)
* [COVID-19 Archive](https://www.covid19-archive.com/) is a collection of selected COVID-19 related news articles, categorized by date.
* [DarwinAI Open-Sources COVID-Net as Medical Imaging in COVID-19 Diagnosis Debate Continues](https://medium.com/syncedreview/darwinai-open-sources-covid-net-as-medical-imaging-in-covid-19-diagnosis-debate-continues-99d1d5491c13)
* ACR [COVID-19 Clinical Resources for Radiologists](https://www.acr.org/Clinical-Resources/COVID-19-Radiology-Resources)
* [COVID-19 Resource Centre](https://www.thelancet.com/coronavirus) - The Lancet 
* [COVID-19 free images](https://www.shutterstock.com/search/covid-19) by shutterstock 
* [Imaging COVID-19 News](https://healthmanagement.org/c/imaging/covid-19)
* [COVID-19 Information](https://hub.jhu.edu/novel-coronavirus-information/) by Johns Hopkins 


## Company and Product
* [COVID-19: Resources & Update](https://www.corporate.siemens-healthineers.com/covid-19/covid-19-resources)by Siemens Healthineers
* [H2O.ai](https://www.h2o.ai/covid-19/)
* [behold.ai](https://www.behold.ai/)
* [Five Companies Using AI to Fight Coronavirus](https://spectrum.ieee.org/the-human-os/artificial-intelligence/medical-ai/companies-ai-coronavirus) by IEEE
* [thirona](https://thirona.eu/) and [Delft Imaging](https://www.delft.care/) - launched [CAD4COVID](https://www.delft.care/cad4covid/)
* [CoreASSIST](https://www.emids.com/coreassist/?cn-reloaded=1): Your COVID-19 Partner
* [COVID-19 Awareness Tool](https://www.tcog.com/news/2020/04/covid-19-awareness-tool/) by TCOG
* [Startup initiatives in times of Covid-19](https://www.imec-int.com/en/istart/startup-initiatives-covid-19)
* [RADlogics](https://www.radlogics.com/coronavirus/)

### AI-assisted COVID-19 applications in Korea: 
* [Vuno](https://covid19.vunomed.com/) offer two solutions - [VUNO Med®-LungQuant™](https://covid19ct.vunomed.com/), [VUNO Med®-Chest X-ray™](https://covid19cxr.vunomed.com/)
* [Lunit](https://lunit.io/ko/covid19) INSIGHT CXR in Coronavirus Response
* Medical IP's [MEDIP COVID19](http://medicalip.com/mobile/shop/covid19.php) - 1st Free Software for AI-driven Automatic CT Analysis of COVID19 Pneumonia
* [The Innovative Korean Companies with solution for COVID-19](https://www.born2global.com/usermediaview.do?media_no=960&media_type=-1&image_yn=All&fbclid=IwAR07_a4zAl2PCaTGtn1sYbcYVjrSQN1RNWGK7H3KmE_3jZt9PifT-bMXANk) by born2global

### China
* [The following list summarizes the known AI-assisted radiological applications in China:](https://www.itnonline.com/article/artificial-intelligence-assisted-radiology-technologies-aid-covid-19-fight-china)

<p align="center">
    <img src="https://www.itnonline.com/sites/default/files/imce-users/ud236/2020-03/AI%20chart%20for%20Chinese%20Companies%20and%20COVID-19.jpg" \>
    <img src="https://www.itnonline.com/sites/default/files/imce-users/ud236/2020-03/AI%20chart%20for%20Chinese%20Companies%20and%20COVID-19%202.jpg" \>
    <img src="https://www.itnonline.com/sites/default/files/imce-users/ud236/2020-03/AI%20chart%20for%20Chinese%20Companies%20and%20COVID-19%203.jpg" \>
</p>

## Miscellaneous
* [coronastats.co](https://coronastats.co/)
* [coronavirus.app](https://coronavirus.app/)
* [Outbreak Info](https://outbreak.info/)
* [Genomic epidemiology of novel coronavirus](https://nextstrain.org/ncov) by nextstrain
* [Coronavirus: A visual guide to the pandemic](https://www.bbc.com/news/world-51235105) by BBC
* [COVID-19 CORONAVIRUS PANDEMIC](https://www.worldometers.info/coronavirus/) by worldmeter 
* [COVID-19 map](https://coronavirus.jhu.edu/map.html) by Johns Hopkins 
* [COVID-19 Realtime dashboard for Korean](https://coronaboard.kr/) - 코로나 보드
* [Coronavirus disease (COVID-19) Situation Dashboard](https://who.sprinklr.com/) by WHO
* [COVID-19 Data Hub](https://www.tableau.com/covid-19-coronavirus-data-resources)
  * [Coronavirus (COVID-19) Viz Gallery](https://public.tableau.com/en-us/s/covid-19-viz-gallery)
  * [Coronavirus in the United States](https://public.tableau.com/profile/stanke#!/vizhome/CoronavirusintheUnitedStates_15855297920450/covid-19)
  * [COVID19 | Trend Tracker](https://public.tableau.com/profile/jonas.nart#!/vizhome/COVID19_15844962693420/COVID19-TrendTracker)
* [COVID-19 Projections](https://covid19.healthdata.org/projections) by IHME
* [Coronavirus Disease (COVID-19) – Statistics and Research](https://ourworldindata.org/coronavirus) by Our World in Data
  * [Case fatality rate of the ongoing COVID-19 pandemic](https://ourworldindata.org/grapher/coronavirus-cfr?country=ITA+KOR+OWID_WRL+SGP+SWE+ESP+USA+FRA+GBR)
  * [Total confirmed cases of COVID-19](https://ourworldindata.org/grapher/covid-confirmed-cases-since-100th-case)
  * [COVID-19: Total confirmed cases vs. confirmed deaths](https://ourworldindata.org/grapher/covid-19-total-confirmed-cases-vs-total-confirmed-deaths)
  * [COVID-19: Daily new confirmed deaths - rolling 3-day average](https://ourworldindata.org/grapher/daily-covid-deaths-3-day-average)
  * [Data on COVID-19 testing](https://ourworldindata.org/covid-testing)
* [Free visualization & spatial analysis software to fight COVID-19](https://carto.com/blog/carto-free-for-fight-against-coronavirus/)
  * [Novel Coronavirus (COVID-19) Infection Map](https://hgis.uw.edu/virus/) by the Humanistic GIS Lab at University of Washington - Seattle
  * [Coronavirus Tracker](https://visalist.io/emergency/coronavirus) by Hari Krishna
  * [Confirmed coronavirus cases in Singapore](https://sgwuhan.xose.net/) by @ottokyu
  * [Risk map for the spread of COVID-19](https://covid-19-risk.github.io/map/) for the spread of COVID-19 in Spain, Portgual and Brazil.
  * [State-by-State Map of School-Building Closures](https://www.edweek.org/ew/section/multimedia/map-coronavirus-and-school-closures.html) in the US
  
