# Udacity-Project-1--No_Show_Appointment-
## Project Overview
This is my first project in the Udacity Nano Degree on Data analytics. This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in the analysis.

## Project Steps
> - Defining questions for the analysis.
> - Data Wrangling.
> - Exploratory Data Analysis.
> - Conclusions.
> - Project limitations.

### Defining Questions for the Analysis
Here, all questions for the analysis are outlined. 
The following are set to be answered;
> - What is the age distribution of the patients?
> - What is the gender distribution (male and female)?
> - Patients distribution that went for their appointment.
> - Which of the neighbourhood honoured there appointment and which ones did not?
> - What is the ratio of the people that have benefited from the Bolsa Familia scholarship?
> - Which of the diseases is common among the patients?
> - For the most chronic disease, did the patients honoured their appointment?
> - How does sending an SMS influence patient decision to honour an appointment?
> - What hour of the day do patients mostly visit the hospital?
> - What day of the week do patients mostly visit the medical facility?
> - What month do patients mostly visit the medical facility?
> - What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

### Data Wrangling
Before the commencement of the analysis on the available from the no-show-appointment file, a clean data is neccessary. The following steps were followed in the ensuring a clean data.
> -  Gather: Using pandas to import the no_show_appointment csv file into the python environment.
> -  Assess: checking for quality and tidiness issues in the imported data file. Anumber of issues were identified and worked on.
> -  Clean: This is where I acted on the assessments made to improve the quality and tidiness of the dataset before analysis.

### Exploratory Data Analysis
All identified questions are assessed and interpreted using appropriate visualizations.

### Conclusion
Conclusions are made based on the questionssuggested and analysis completed.Some key conclusions are;
> - 80% of Male and Female showed up for their scheduled appointment.
> - 80% of the people showed-up for their appointment and only about 20% missed their appointments.
> - The Parque Industrial had the highest turnout followed immediately by Ilha Do Boi.
> - Ilhas Oceanicas De Trindade had the highest missed appoinments.
> - Sending an sms does not guarantee whether a person will go for an appoinment or not.

### Project limitations
Some key limitations during the project;
> - The dataset contains information for only 8 months in 2016. Out of this 8 months, 3 months have very little information. Moreso, the missing 4 months from the dataset could contain information that would have been more useful in the data analysing.
> - Only 10% of the people in the dataset received the Bolsa scholarship. This indicates that the data was insufficient to truly make concrete conclusion on the dataset.
> - Moreso, only 35% of people received sms alerts leaving 65% without sms notification for their appoinment. Considering that sms notification should be an important factor, unfortunately, only a small fraction of the people received it.
