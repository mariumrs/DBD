# Deciphering Big Data 

## About me

Im a Masters student pursuing Data science based in UAE

### Skills

- Data Anlysis
- Business analytics
- Data Visualization
- Quick and flexible with different domains

### Expertise

Python, R, Google Analytics 4, Tableau, power BI, Jira, SQLplus , MySQL, SAP

## Projects

Here is a summary of all the details of my projects so far while going through the deciphering big data course. 

### Deciphering Big Data [Jan 2025]

#### Introduction

Welcome to my e-portfolio, a curated collection of my journey through the exploration of data diversity, collection methods, and the intricate process of data wrangling. Throughout this module, I have delved into the transformation of raw data into a refined, usable format, enhancing its quality by eliminating redundancies and ensuring its readiness for various applications.

#### Expected Learning outcmes:
- Identify and manage challenges, risks, and opportunities in data wrangling.
- Analyze data problems and apply appropriate tools and techniques to clean, prepare, and evaluate data.
- Design and develop solutions for processing datasets and solving complex problems.
- Evaluate different data types, storage formats, and their requirements.
- Assess data collection methods and ensure data integrity and reliability.
- Analyze data exploration techniques and ensure its readiness for use.
- Understand database design, modeling, and management systems.
- Explore machine learning concepts and their role in handling big data.
- Develop teamwork skills for effective collaboration in professional environments.  

#### Applied concept 
This portfolio showcases my understanding of Data types, storage formats and the critical evaluation of data integrity and reliability. Aditionally it highlights my proficiency in utilizing tools and methodologies to adress data wrangling challanges as well as my ability to design and implement solutions for complex data problems 
 
## Collaborative discussion 1 : The Data Collection Process 
### Learned objectives:
- Critically evaluated the rationale behind the Internet of Things (IoT) using insights from Huxley et al. (2020).
- Identified opportunities, limitations, risks, and challenges associated with large-scale IoT data collection.
- Reviewed Lecturecast materials and also went through some of the posted comments to makeup the collabrative discussion
  
The final collaborative piece can be found on the git hub repository.

[Collabrative Discussion 1](https://github.com/mariumrs/DBD/blob/main/Collabrative%20Discussion%20Summary%201.docx)
 
## Collaborative discussion 2: Comparing Compliance Laws 
### Learned objectives:
- Compared the GDPR’s securing personal data principle with similar compliance laws in my country of residence or the ICO’s standards in the UK.
- Analyzed the GDPR’s security requirements, including exemptions, and discussed their alignment or divergence with other regulations.
- demonstrated comprehension of GDPR’s security standards and application in the datawrangling process 
- Identified challenges, risks and opportunities related to securing personal data in compliance with regulatory frameworks.

The final collaborative piece can be found on the git hub repository.
[Collabrative Discussion 2](https://github.com/mariumrs/DBD/blob/main/Collabrative%20Discussion%20Smmary%202.pdf)

## Web scraping with Python 
### Learned objectives:
To demonstrate web scraping using Python's BeautifulSoup and Requests libraries by searching for "Data Scientist" and parsing the results into a JSON file.

### Python code steps 
1. Send request using request module
2. Parse the response HTML with BeautifulSoup / ensure library is installed 
3. Extracts job titles and associated information for the keyword "Data Scientist"
4. Save the extracted data into a file (JSON)

[Code Available](WebScraping)

## Normalization Task  
### Learned objectives:
- Data Cleaning: Prepare datasets by removing empty rows, fixing missing data, and ensuring atomic values.
- Was able to normalize data in 3 steps
- Relational Design: Create linked tables with logical groupings for efficiency.

### Approach 
3 steps towards normalization 
- 1NF:
  - each row is unique and data such as first name and last name is parsed into two different fields in the students table
 <img width="722" alt="image" src="https://github.com/user-attachments/assets/ebb4dd98-5099-444a-93d2-dd5e6b93dd6b" />
  
- 2NF
  - removing partial dependency by ensuring tables completely depend on primary keys and not on different variables
    <img width="310" alt="image" src="https://github.com/user-attachments/assets/394ade36-4a41-4c7f-bc0b-3cb69a6407b6" />

  - Data is segregated into two tables courses containing unique sourse information and exam containing unique values
   <img width="229" alt="image" src="https://github.com/user-attachments/assets/94ac5a67-379d-4f36-8484-4e315f2b38df" />
   <img width="275" alt="image" src="https://github.com/user-attachments/assets/911fe4f6-8cfb-40af-b61e-7b6b3da1c8e2" />

- 3NF
  - removing non-key attribute to ensure there is no transitive dependency
  - Students Table contains unique student data with no redundant information.
  <img width="341" alt="image" src="https://github.com/user-attachments/assets/c23f4605-c869-4c0f-a2e0-bee6c5ad9f61" />
  
  - Courses Table Contains unique course details ensuring no attribute depends on a non-primary key
 <img width="231" alt="image" src="https://github.com/user-attachments/assets/b99f846e-0a8e-4756-b397-c2f99dfe6304" />

  - Exams Table links students and courses representing exam-related data
 <img width="278" alt="image" src="https://github.com/user-attachments/assets/e475055c-c091-4c5e-8415-b1bf7d30e6b7" />

While building the DBMS the only issue regarding integrity was needing a primary key for courses table in the 3NF 

The final [normalized tables](https://github.com/mariumrs/DBD/blob/main/normalization%20task.xlsx)

## Assignment 1 and team work 
### Learned objectives:
- Analyzed data wrangling challenges like missing values and duplicates, and applied normalization and ETL processes to clean and prepare data.
- Optimized Data Management by researching on usages of indexing, partitioning, and security measures (encryption, role-based access) to ensure data integrity and performance.
- Proficiency in MySQL: Created a databse format that allowed the data to be querried and later transformed into a Database 
- Collaborated effectively by working in a virtual team, adopting real-life roles to design and implement the database
- How to work as a team to brainstorm ideas and see more perspectives.
- Solved problems and Improved Systems: Evaluated the design for scalability, proposed ML/NLP integration, and suggested GDPR compliance for future-proofing.
- Aligned with business goals ensuringthe database enhances customer satisfaction and loyalty, while identifying areas for improvement like real-time analytics.

### Meeting disucssions   
- Meeting 1 : self introductions and disucssion to understand the assignment and what it entails
- Meeting 2: Creating an overview of the assignment and discussion the business industry we would like to focus on that would cover all aspects of the requirements can be seen in [Overview](https://github.com/mariumrs/DBD/blob/main/Assignment%201/assignment_overview.pdf)
- Meeting 3: Creating a [mockup ERD](https://github.com/mariumrs/DBD/blob/main/Assignment%201/ERD%20-%20Retail.png) by highlighting processes that should be in place 
- Meeting 4: Creating [assumptions](https://github.com/mariumrs/DBD/blob/main/Assignment%201/ERD_assumptions.pdf) for ERD and disucssing how to normalize the ERD data
- Meeting 5 Finalizing the ERD and dividing sections of the document. 
- Meeting 6: [Final](https://github.com/mariumrs/DBD/blob/main/Assignment%201/Project%20Report.pdf) review as well as compilation, adjusting document in adherence to the world limit

All source material of assignment 1 can be found in the link below
[Assignment published material](https://github.com/mariumrs/DBD/tree/main/Assignment%201)

## API Security Requirements 
### Learnt Objectives 
- Identified and mitigated security risks associated with API usage and data sharing.
- Gained proficiency in securing API connections using authentication, rate limiting, and input validation.
- Improved skills in handling and storing data securely across JSON, XML, and SQL formats.
- Developed error-handling techniques to maintain data integrity during API interactions.
- Enhanced collaboration 
- Strengthened problem-solving abilities for addressing data wrangling challenges.

### API Requirements : Coin Gecko 
## Summary 
evaluated the security requirements of the CoinGecko API to enable data sharing and connectivity between Python code and file formats like JSON, XML, and SQL. The focus was on mitigating risks and ensuring secure data handling.

Key security measures included:
- Using API keys for authentication and adhering to rate limits to avoid disruptions.
- Validating API responses to ensure data integrity and handling errors in case of incomplete data.
- Sanitizing inputs to prevent injection attacks and securing API keys with environment variables.
- Encrypting sensitive data when storing it in databases or exporting it to JSON/XML.
- Monitoring API usage and staying updated with CoinGecko’s security guidelines.

[Code](API)

