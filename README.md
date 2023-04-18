# MEDICARE-FRAUD-DETECTION

#INTRODUCTION:

Healthcare has and perpetuates to be an integral component in people’s lives.The human body is a compound structure. Hence, it is essential to havespecialist physicians qualified to diagnose and treat diseases in different parts ofthe body. This induces several types of treatment procedures that physicianscarry out for patients in different specialties. The aim of the health industry is to successfully serve as many patients as possible. But with every treatment thereis a price associated with every service provided. Physicians, drug dealers and medical staff have to be paid for their time and prowess including various medical amenities. Oftentimes these prices are not affordable to the patients.Therefore, insurance schemes are used to dispense costs over all patients in the healthcare system and pay for the requisite people and equipment. As with any insurance system, there is a possibility for misuse or fraud activities. Healthcare fraud is increasingly apperceived as one of serious social concerns. Clearly, healthcare fraud is a problem for the government and there is a need for more effective detection methods. To detect healthcare fraud, it requires great amount of efforts with extensive medical knowledge. Traditionally, healthcare fraud detection greatly depends on the experience of domain experts, which is erroneous enough, expensive and time consuming. Manual detection of healthcare fraud involves a few auditors who manually review and identify the suspicious medical insurance claims which requires much effort. But the modern advances of machine learning and data mining techniques led to more efficient and automated detection of healthcare frauds. There has been a growing interest in mining healthcare data for fraud detection in the recent years. This paper reviews the various approaches used for detecting the fraudulent activities in Health insurance claim data.

#PROBLEM STAEMENT:

Building an innovative data science model that help in predicting fraud in medical insurance industry by using real time analysis and classification algorithm. This tool can be used by the government so that it benefits the patients, pharmacy, doctors which eventually help in gaining credibility to industry, tackle the increasing costs of healthcare and handle the impact of fraud. Medicinal services misrepresentation is a principle issue that causes generous fiscal misfortune in Medicare/Medicaid and protection industry. The Centres for Medicare and Medicaid Services (CMS) have arrangement Medicare Part D programs since 2006. CMS depends on it to identify and forestall extortion, waste and maltreatment in Part D program. Be that as it may, utilizing the customary techniques, the misrepresentation location is directed on arbitrary examples by human specialists. The results are the examples may be deluding or manual identification is exorbitant. As per Office of Inspector General report: Since 2006, the Medicare Fraud has quickly expanded. The extortion designs incorporate the accompanying four sorts: • Fraud by Service Providers (Doctors, hospitals, pharmacies) • Fraud by Insurance subscribers (patient or patient’s employers) • Fraud by insurance carriers • Conspiracy Frauds (involved with all parties).The main objectives of this project are: • Build a basic Data Model to show the connections among the distinctive datasets and distinguish the key capabilities for extortion recognitions • Build a thorough AI model to recognize misrepresentation design dependent on the various highlights: Service Providers (Doctors, Pharmacies), Insurance supporters (patients), Geo-segment and usually misuse drugs medicines • Setup a benchmark measurement to quantify and assess the test result • Market-prepared item

#DATASETS:

The following public datasets were used: • Part D Prescriber Dataset • Excluded (LEIE) dataset • Payment Received dataset Dataset Link: • CMS Part D datasets: https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Part-D-Prescriber.html • LEIE Datasets: https://oig.hhs.gov/exclusions/exclusions_list.asp Office of Inspector General Reports https://oig.hhs.gov/reports-and-publications/portfolio/index.asp • FDA datasets https://www.fda.gov/Drugs/InformationOnDrugs/ucm079750.htm#collapseOne

#METHODOLOGY:

The methodology of this project will follow the below procedures: • Data exploration, cleansing and preparation • Build a simple data model to join all datasets • Feature engineering to choose the effective feature sets for the different fraud patterns • Build a machine learning model to detect the different fraud patterns.

#CONCLUSION:

In this paper, healthcare fraud, types of healthcare frauds, types and sources of healthcare data, and methods for healthcare frauds were studied. Various studies
are reviewed in the literature. It is deduced that in the healthcare industry,‘Data’ is a paramount issue. The major part of the data comes from governmental resources and private insurance companies. Mainly, machine learning and data mining are used for Healthcare fraud detection. Supervised, unsupervised and semi-supervised learning are the three categories of Machine learning approaches. In most of the cases, semi-supervised learning approaches are used by many researchers. But, to detect frauds in healthcare system more efficiently, new semisupervised learning approaches can be proposed in few cases. But, to conceal all the instances of the healthcare fraud, there doesn’t exist any particular standard approach or patterns. It can an be concluded from this review that the advanced machine learning techniques and newly acquired sources of the healthcare data would be forthcoming subjects of interest in order to make the healthcare affordable, to improve the effectiveness of healthcare fraud detection and to bestow top quality on healthcare systems.
#REFERENCES
[1] Abdallah, A., Maarof, M. A., & Zainal, A. (2016). Fraud detection system: A survey. Journal of Network and Computer Applications, 68, 90-113.
[2] Behdad, Mohammad, et al. "Nature-inspired techniques in the context of fraud detection." IEEE Transactions on Systems, Man, and Cybernetics, Part C(Applications and Reviews) 42.6 (2012): 1273- 1290.
[3] Konasani, Venkatareddy, Mukul Biswas, and Praveen Krishnan Koleth."Healthcare fraud management using big data analytics." An Unpublished eport by Trendwise Analytics, Bangalore, India (2012).
[4] National Health Care Anti-Fraud Association. "Health Care Fraud–A serious andCostly Reality For All Americans." April2005 (2007).
[5] Yang, Wan-Shiou. "A Process Pattern Mining Framework for the Detection f Health Care Fraud and Abuse." National Sun Yat-Sen University, Taiwan
(2003)..
[6] Liu, Qi, and Miklos Vasarhelyi. "Healthcare fraud detection: A survey and a lustering model incorporating Geo-location information." In 29th World
Continuous Auditing and Reporting Symposium (29WCARS), Brisbane,Australia. 2013..
[7] Thornton, Dallas, Roland M. Mueller, Paulus Schoutsen, and Jos vanHillegersberg. "Predicting healthcare fraud in medicaid: a multidimensionaldata model and analysis techniques for fraud detection." Procedia technology 9(2013): 1252-1264.
[8] Bauder, Richard A., Taghi M. Khoshgoftaar, Aaron Richter, and Matthew rland. "Predicting medical provider specialties to detect anomalous insurance
claims." In Tools with Artificial Intelligence (ICTAI), 2016 IEEE 28th
International Conference on, pp. 784- 790. IEEE, 2016.
[9] Branting, L. Karl, Flo Reeder, Jeffrey Gold, and Timothy Champney."Graph analytics for healthcare fraud risk estimation." In Advances in Social
Networks Analysis and Mining (ASONAM), 2016 IEEE/ACM InternationalConference on, pp. 845-851. IEEE, 2016.
[10] Musal, Rasim Muzaffer. "Two models to investigate Medicare fraud within nsupervised databases." Expert Systems with Applications 37, no. 12 (2010):
8628-8633.
[11] Copeland, Leanndra, Dana Edberg, Anna K. Panorska, and Jeanne Wendel."Applying business intelligence concepts to Medicaid claim fraud detection."
Journal of Information Systems Applied Research 5, no. 1 (2012): 51.
[12] Bauder, Richard A., and Taghi M. Khoshgoftaar. "A probabilisticprogramming approach for outlier detection in healthcare claims." In Machine
Learning and Applications (ICMLA), 2016 15th IEEE International Conference
on, pp. 347-354. IEEE, 2016.
[13] Bauder, Richard A., and Taghi M. Khoshgoftaar. "A novel method forfraudulent medicare claims detection from expected payment deviations
(application paper)." In Information Reuse and Integration (IRI), 2016 IEEE
17th International Conference on, pp. 11-19. IEEE, 2016.
[14] van Capelleveen, Guido, Mannes Poel, Roland M. Mueller, DallasThornton, and Jos van Hillegersberg. "Outlier detection in healthcare fraud: A
case study in the Medicaid dental domain." International journal of accounting
information systems 21 (2016): 18-31.
[15] Rudman, William J., John S. Eberhardt, William Pierce, and Susan HartHester. "Healthcare fraud and abuse." Perspectives in Health Information
Management/AHIMA, American Health Information Management Association6, no. Fall (2009).
[16] Joudaki, Hossein, Arash Rashidian, Behrouz MinaeiBidgoli, Mahmood ahmoodi, Bijan Geraili, Mahdi Nasiri, and Mohammad Arab. "Using data
mining to detect health care fraud and abuse: a review of literature." Globaljournal of health science 7, no. 1 (2015): 194.
[17] Jyothsna, V., VV Rama Prasad, and K. Munivara Prasad. "A review ofanomaly based intrusion detection systems." International Journal of Computer
Applications 28, no. 7 (2011): 26-35.
[18] Li, Jing, Kuei-Ying Huang, Jionghua Jin, and Jianjun Shi. "A survey onstatistical methods for health care fraud detection." Health care management
science 11, no. 3 (2008): 275-287.
[19] Srinivasan, Uma, and Bavani Arunasalam. "Leveraging big data analyticsto reduce healthcare costs." IT professional 15, no. 6 (2013): 21-28.
[20] Feldman, Keith, and Nitesh V. Chawla. "Does medical school trainingrelate to practice? Evidence from big data." Big data3, no. 2 (2015): 103-113.
[21] Ko, Joan S., Heather Chalfin, Bruce J. Trock, Zhaoyong Feng, Elizabeth
Humphreys, Sung-Woo Park, H. Ballentine Carter, Kevin D. Frick, and MisopHan. "Variability in Medicare utilization and payment among urologists."
Urology 85, no. 5 (2015): 1045- 1051.

