# Advanced Regex for Data Mining, Extraction, and Scraping

## 📌 Introduction
This repository provides advanced **Regular Expressions (Regex)** techniques for **Data Mining, Data Extraction, and Web Scraping**. The notebook explores practical use cases where regex can efficiently extract structured data from unstructured , raw, text, including **log files, web data, textual datasets, and scraped content**.

## 🚀 Features
- Advanced **Regex patterns** for text mining
- Extracting **structured data** from raw text
- Web Scraping techniques combined with **Regex**
- Handling **complex text formats**
- Use cases with **Python & Pandas**
- Parsing **HTML/XML, logs, and datasets**

## 🛠️ Technologies Used
- **Python** (pandas, re, BeautifulSoup, requests)
- **Jupyter Notebook** for interactive learning
- **Regex (Regular Expressions)**
- **Web Scraping** using BeautifulSoup

## 📂 Contents
- `Advance Regex For Data Mining.ipynb` - The core notebook with regex techniques
- `examples/` - Sample text files and datasets for regex-based extraction

## 📖 Use Cases
### ✅ **Data Mining & Extraction**
- Extracting dates, phone numbers, emails
- Identifying patterns in unstructured data
- Cleaning and structuring messy text

### ✅ **Web Scraping & Parsing**
- Extracting data from HTML/XML pages
- Filtering and cleaning scraped content
- Automating data extraction from websites

### ✅ **Log File Analysis**
- Parsing log files for insights
- Extracting error messages, timestamps
- Analyzing structured logs using regex

## 🔧 Installation & Setup
### **1️⃣ Clone the Repository**
```bash
 git clone https://github.com/tejask0512/Advance-Regex-For-Data-Mining-Extraction.git
 cd Advance-Regex-For-Data-Mining-Extraction
```

### **2️⃣ Install Dependencies**
```bash
pip install pandas beautifulsoup4 requests
```

### **3️⃣ Run the Jupyter Notebook**
```bash
jupyter notebook
```
Open `Advance Regex For Data Mining.ipynb` and start exploring regex techniques!

## 📌 Examples
### **Extracting Variety of dates from Text**
```txt
03/25/93 Total time of visit (in minutes):
6/18/85 Primary Care Doctor:
sshe plans to move as of 7/8/71 In-Home Services: None
7 on 9/27/75 Audit C Score Current:
2/6/96 sleep studyPain Treatment Pain Level (Numeric Scale): 7
.Per 7/06/79 Movement D/O note:
4, 5/18/78 Patient's thoughts about current substance abuse:
10/24/89 CPT Code: 90801 - Psychiatric Diagnosis Interview
(2/03/78) TSH-0.90 Activities of Daily Living (ADL) Bathing: Independent
2/11/2006 CPT Code: 90791: No medical services
Pt is a 21 year old, single, heterosexual identified, Liechtenstein male. He resides in Rabat, in a rented apartment, with a roommate. He has not graduated from high school nor has he earned his GED. He has been working full time, steadily, since the age of 16. He recently left a job at jacobs engineering group where he worked for about 5 years. He started working at becton dickinson a few weeks ago. Referral to SMH was precipitated by pt seeing his PCP, Dr. Ford, for a physical and sharing concerns re: depression. He was having suicidal thoughts the week of 8/22/83 and noticed that his depression and anxiety symptoms were starting to interfere with work. Per Dr. Ford's recommendation, he contacted PAL for assistance. When screened for substance use, pt was referred to SMH for an intake. Pt was scheduled to be seen last week due to urgency of his depression and SI, but missed the intake appointment due to getting extremely intoxicated the night before. Pt presents today seeking individual therapy and psychiatry services to address longstanding depression.
PET Scan (DPSH 5/04/74): 1) Marked hypometabolism involving the bilateral caudate nuclei. This is a non-specific finding, although this raises the question of a multisystem atrophy, specifically MSA-P (striatonigral degeneration), 2) Cortical hypometabolism involving the right inferior frontal gyrus. This is a non-specific finding of uncertain significance, and is not definitively related to a neurodegenerative process, although pathology in this region is not excluded
7/20/2011 [report_end]
6/17/95 Total time of visit (in minutes):
06 May 1972 SOS-10 Total Score:
25 Oct 1987 Total time of visit (in minutes):
14 Oct 1996 SOS-10 Total Score:
30 Nov 2007 CPT Code: 90801 - Psychiatric Diagnosis Interview
h missed intake office visit on 28 June 1994 at Sierra Vista Nursing HomeSuicidal Behavior Hx of Suicidal Behavior: Yes
14 Jan 1981 SOS-10 Total Score:
.On 10 Oct 1985 patient began FMLA from work.
26 May 1974 Primary Care Doctor:
short term partial hospital program at Pine Rest Hospital starting 10 Feb 1990
23 Aug 2000 Primary Care Doctor:
.The patient brought himself to APS on 26 May 2001 for ONE MONTH HISTORY of recurrence of increased depressed and anxious mood, with
see 21 Oct 2007 Schroder Hospital discharge summaryViolent Behavior Hx of Violent Behavior: Yes
19 Oct 2016 Communication with referring physician?: Done
dON 05 Mar 1974
29 Jan 1994 Primary Care Doctor:
see 21 Oct 1978 Schroder Hospital discharge summaryHx of Non Suicidal Self Injurious Behavior: Yes
.On 18 August 1975 patient presented to BH ED/APS for psychological distress over binge eating and weight concerns, as well as acknowledging chronic intermittent SI but no acute SI; otherwise good response to Abilify 20 mg QD.  Patient was discharged home to follow up with Urgent care TODAY.
11 Nov 1996 CPT Code: 90792: With medical services
01 Oct 1979 Primary Care Doctor:
July 25, 1983 Total time of visit (in minutes):
August 11, 1989 Total time of visit (in minutes):
April 17, 1992 Total time of visit (in minutes):
EKG July 24, 1999: QTc 496 msPertinent Medical Review of Systems Constitutional:
July 11, 1997 CPT Code: 90792: With medical services
s Gale Youngquist is a 22 yo single Caucasian female who presents to the HJH Psychiatry for an evaluation of her current eating disorder status and treatment needs.  She shared that she began restricting at age 11 yo but could not identify any specific triggers.  "Mostly I wouldn't eat at school, and then I'd have dinner at home, but some days not," per pt. Her parents and ski coach started noticing that "I wasn't eating and was losing weight."  She began outpatient treatment at age 11, and has been in and out of outpatient and higher levels of care since then, including multiple emergency room visits and against medical advice (AMA) departures.  Most recently, she left Jefferson County Health Delegates AMA on Sep. 10, 1974.  "They weren't saying I was ready to go, but insurance pulled out," per pt.  She said she felt both dissappointed but also relieved to leave residential care to move back home w/ her mother.
.August 14, 1981- bad reaction to SpiceK2 - synthetic MJ- admitted to Crete Manor, Mcalester.
Nov 11, 1988 Total time of visit (in minutes):
e June 13, 2011 Suicidal Behavior Hx of Suicidal Behavior: Uncertain
The patient reports having had an endoscopy, colonoscopy and abdominal CT at an outside hospital in the Gravette Medical, which were read as negative. The patient also reports a number of labs which were also normal in September 2008. Prior relevant imaging:
February 1983 Primary Care Doctor:
sKern Hospital March 1983 for SI
cutting of wrist and thigh x 2years - stopped since Aug 1979
B/R Natchez, GA on a commune. Completed 1 year of medical school. Married to husband for 50+ years. Moved to Maine and later settled in West Hurley, AK. HAs 2 children and 5 grandchildren. Worked as notary public for the local government for over 50 years. Husband now in nursing home and she has moved in with her daughter's family in Emerald Isle, AK as of Jan 2009. No access to firearms. Past verbal, emotional, physical, sexual abuse: No
HH, Janaury 1993
6/1998 Primary Care Doctor:
s 52 y/o MWM h/o chronic depression, anxiety, adhd.  Here for psychopharm transfer in the context of his recent psychiatrist Dr. Blankenship's departure in 6/2005.  Patient endorses a long history of depression "ever since childhood" which wodesned in college and while patient was in Doctors Without Borders--was stationed in Bulgaria as a medical assistant, and left after several months: "I was so depressed I only weighed 120 lbs."
10/1973 Hx of Brain Injury: Yes
9/2005 Primary Care Doctor:
s 03/1980 Positive PPD: treated with INH for 6 months
12/2005 Family Psych History: Family History of Suicidal Behavior: None
5/1987 Primary Care Doctor:
5/2004 Primary Care Doctor:
aS/P suicide attempt 2011 Hx of Outpatient Treatment: Yes
Patient has a history of suicidal ideation with plan. She denied ever attempting to take her life, but noted coming close to it in the past. Patient also reported that she has not had suicidal ideation, intent, or plan since 1997, other than this one instance this past week of passive ideation. Patient committed to the safety plan, which is to call 911, or call her sister if she is unable to call 911 (who would call 911 for her), or go to the nearest ER and then page the current writer. She also has the number for the crisis hotline and related that she could also call her mental health counselor that she sees at DMC. Multi-Axial Diagnoses/Assessment Anxiety Disorders 300.3 Obsessive Compulsive Disorder
Born and raised in Fowlerville, IN.  Parents divorced when she was young, states that it was a "bad" divorce.  Received her college degree from Allegheny College in 2003.  Past verbal, emotional, physical, sexual abuse: No
y1983 Clinic Hospital, first hospitalization, s/p SA by OD
tProblems Urinary incontinence : mild urge incontinence, noted in 1999.
.2010 - wife; nightmares and angry outbursts; drinking a lot; living in deceased grandmother's house with wife.  Working for American Electric Power- billing.
shx of TBI (1975) ISO MVA.Medical History:
```

### **Scraping Data from Web Pages**
```python
from bs4 import BeautifulSoup
import requests

url = "https://example.com"
response = requests.get(url)
soup = BeautifulSoup(response.text, 'html.parser')

# Extracting all links
tags = soup.find_all('a')
links = [tag.get('href') for tag in tags if tag.get('href')]
print(links)
```

## 📢 Contribution
Feel free to contribute to this repository by adding more **regex-based data extraction techniques** or **web scraping examples**. Fork the repo, create a new branch, and submit a **pull request (PR)**.

## 📜 License
This project is licensed under the **MIT License**.

## 🔗 Connect
👤 **Tejas Kamble**  
🌐 [Website](https://tejaskamble.com)  
📧 [Email](mailto:tejask0512@example.com)  
🐙 [GitHub](https://github.com/tejask0512)

Happy Coding! 🚀

