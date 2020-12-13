# Smile On Project

Smile On 60+ is a Tennessee program that offers oral healthcare to Tennessee residents that are 60 years and older, low income, and don't have dental insurance. The program provides support of oral healthcare, education, and transportation.  
### More information can be found:
- https://www.tn.gov/aging/administration/seniortrust-eldertrust.html
- https://interfaithdentalclinic.com/smile-on-60/

# Data Questions  
For this project we will be answering two questions to evaluate the Smile On program:  
1. Has the Smile On program been effective?  
2. Is the Smile On program being used by people in the area where tooth loss is greatest?  

# Smile On Data
Information about patients is gathered during different interactions (initial visit, checkups, etc.). The data in the `data` folder include records through November 28. There is also a data dictionary that contains some useful information about the different columns.

# Team Contribution
For this team project, my team decided to investigate the number of patients whose mouths were 'restored to function' as of their last dental visit with the program and made this one of our metrics for determining program effectiveness. A patient who has been 'restored to function' is able to chew and has their front six teeth present, which we know equates to improved quality of life. Our visual highlights the clinics that were able to restore the most patients to function.

![chart](/data/smile_on_visual.png)

We also created the visual showing the prevalence of complete tooth loss in major cities in Tennessee and highlighted Chattanooga as a potential opportunity for Smile On to increase their presence. Lastly, we were involved in creating some of the visuals about the demographic make-up of their current patients. The full presentation is available in the repository.

This projects required us to continually refine our approach in handling null values and be critical about how we displayed the data and how we communicated our approach to the client. It also required us to be intentional and persistent in our communication with other groups in the class since our visuals would become a part of a larger story.

# Centers for Medicare and Medicaid Services  
For comparing the Smile On program to Tennessee overall you will use data from the Centers for Medicare and Medicaid Services (CMS). Medicare is the program that provides financial assistance to elderly patients. There are different parts of Medicare:
- Part A: Inpatient Hospitalizations
- Part B: Outpatient Services
- Part C: Medicare Advantage
- Part D: Prescription Drug Coverage  

Original Medicare (Parts A and B) don't cover oral healthcare procedures unless they are incidental with other healthcare needs, such as an accident or in preparation for another procedure (more information here: https://www.cms.gov/Medicare/Coverage/MedicareDentalCoverage/index). Medicare Part C (Medicare Advantage) include healthcare plans that are approved by the government and can include more typical oral healthcare procedures (cleanings, X-Rays, extractions, etc). These data, however, are not publicly available and only recently became available to researchers.  

You are strongly encouraged to look at the CMS data (data.cms.gov) to find datasets that may be useful for this project. A few useful starting points are:  
Physician and Other Supplier Payments: https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Physician-and-Other-Supplier2017  
Hospital Outpatient: https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Outpatient  
Healthcare Common Procedure Coding System (HCPCS) - Ambulatory Payment Classification (APC) Crosswalk: https://www.cms.gov/Medicare/Medicare-Fee-for-Service-Payment/HospitalOutpatientPPS/Addendum-A-and-Addendum-B-Updates  

CMS uses codes to describe the different procedures. Sometimes there are descriptions of what the codes mean but not always. Additionally, there are different code systems, for out use cases the main ones are Healthcare Common Procedure Coding System (HCPCS) and Ambulatory Payment Classification (APC). These can be used to describe similar procedures, just in different settings. The `crosswalk` file will be useful in understanding the codes meanings and how the different code systems relate to each other.

# Timeline
11/30: Project Kickoff  
12/2 Morning: Team/Instructor Check-ins  
12/3 Afternoon: Team/Instructor Check-ins  
12/4 Afternoon: Presentation Walkthrough  
12/7 Morning: Team/Instructor Check-ins  
12/8 Afternoon: Final Presentation  
