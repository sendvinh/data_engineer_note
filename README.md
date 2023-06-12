# data_engineer_note

## 1. Introduction to Data Engineering

**Data Engineering** convert raw data into usable data  
Extract, integrate, and organize data from disparate sources  
Clean, transform, and prepare data  
Design, store, and manage data in data repositories  
Skills:  
Good knowledge of programming  
Sound knowledge of systems and technology architectures  
In-depth understanding of relational databases and non-relational datastores  
    
**Data Analytics** use this data to generate insights  
Inspect and clean data for deriving insights  
Identify correlations, find patterns, and apply statistical methods to analyze and mine data  
Visualize data to interpret and present the findings of data analysis  
Ex: Are the users search experiences generally good or bad with the search functionality on our site?  
What is the popular perception of peple regarding our rebranding initiatives?  
Is there a co-relation between sales of one product and another?  
Skills:  
Good knoledge of spreadsheets, wrting queries, use statistical tools to create charts and dashboards  
Programming skills  
Strong analytical and story-telling skills  

**Data Scientist** use DA and DE to predict the future suing data from the past  
Create predictive models using Machine Learning and Deep Learning  
Ex: (related to predition)  
How many new social media followers am I likely to get nex month?  
What percentage of my customers am I like ly to lose to competition in next quarter?  
Skills:  
Mathematics and Statistics  
Programming languages, databaases, building datamodels  
Domain knowledge  

**Business Analyst and BI analyst** leverage the work of DA and DS to look at possible implications for their business and **actions** they need to take or recommend.

#### Field of data engineering involves: 
**Collecting source data**: extrating, integrating, oragnizing data from disparate sources  
develop tool, workflow, process to acquire data from multiple sources   
design, build, maintain scalable data architecture to store data  
**Processing data**: cleaning transforming, preparing data to make it usable   implement, maintain distributed systems for large scale processing of data    
design pipelines for ETL of data into data repositories  
design/implement solution for validating and safeguarding quality, privacy and security of data  
optimize tools, systems, and workflows for performances, reliability and scalablity  
ensure data meets all regulatory and compliance guidelines  
**Storing data** for reliability and easy availability of data storing data for reliability  
architect/implement data stores for the storage of processed data  
ensure systems are scalable  
ensure data privacy, security, compliance, monitoring, backup and recovery  
**Making data available to users securely**  
APIs, services, and programs for retrieving data for end-users  
Dashboard and interface that present data to user  
**--> Data Engineering is a team sport, no one person is expected to have all the knowledge, skills, and specializations required for the wide-ranging tasks covered within the scope of data engineering**

#### Resposibilities of DE:  
ETE data from disaparate sources   
Preapare data for analysis and reporting by transforming and cleansing   
Design and ma nage data piplines   
Setup and manage the infrastructure...  
**Skills of DE**:  
**Technical skills**:  
Operating Systems: UNIS, Linux, Windows...  
Infrastructure Components: VM, Networking, App Services (load balancer, perforamance monitoring), Cloud-based services  
Databases and Data Warehouses: RDBMS, NoSQL(redis, mongodb, cassandra, neo4j), Data Warehouses(Amazon Redshift...)  
Data Pipelines: Apache Beam, Apache Airflow, Dataflow  
ETL tools: IPM infosphere, Aws glue  
Languages: Query(Sql, Sql-like), Programming(Java, Python). Shell and scripting language  
Big data process tools: hadoop, hive, spark  
**Functional skills**:  
Convert requirement to technicall specs  
...  
**Soft skills**:  
Communication in tech and non-tech  
...

#### Data Engineer Ecosystem  
Data types:  
Structured data: database, spreadsheets...  
Semi-structured data: email...  
Unstructured data: photos, videos, text files, pdfs, social media content...  
Data sources:  database, apies, web services, stream, social media, censor...  
Data repositories:  
transactional (OLTP - Online Transaction Processing): tramsactopm database. atm database...  
Analytical (OLAP - Online Analytical Processing): database, data warehouse, data lake, big data store...  
Data integration: collated -> processed -> cleansed -> integrated -> user  
Data pipeline: tools, processes that cover journeey of data from source to destination  
BI and reporting tools:  

#### Big Data  
Velocity: data is being generated extremely fast, in a process that never stops  
Volume: increase inf data store  
Variety: diversity of data, variaty of source  
Vẻacity: quality and origin of data  
Value: turn to valueable data  

#### The different types of Data Repositories include:  

Databases, which can be relational or non-relational, each following a set of organizational principles, the types of data they can store, and the tools that can be used to query, organize, and retrieve data.  
Data Warehouses, that consolidate incoming data into one comprehensive store house.  
Data Marts, that are essentially sub-sections of a data warehouse, built to isolate data for a particular business function or use case.  
Data Lakes, that serve as storage repositories for large amounts of structured, semi-structured, and unstructured data in their native format.  
Big Data Stores, that provide distributed computational and storage infrastructure to store, scale, and process very large data sets.  

#### The ETL, or Extract Transform and Load, Process is an automated process that converts raw data into analysis-ready data by:  
Extracting data from source locations.  
Transforming raw data by cleaning, enriching, standardizing, and validating it.  
Loading the processed data into a destination system or data repository.  

#### The architecture of a data platform can be seen as a set of layers, or functional components, each one performing a set of specific tasks. These layers include:  
Data Ingestion or Data Collection Layer, responsible for bringing data from source systems into the data platform.  
Data Storage and Integration Layer, responsible for storing and merging extracted data.  
Data Processing Layer, responsible for validating, transforming, and applying business rules to data.  
Analysis and User Interface Layer, responsible for delivering processed data to data consumers.  
Data Pipeline Layer, responsible for implementing and maintaining a continuously flowing data pipeline.  


