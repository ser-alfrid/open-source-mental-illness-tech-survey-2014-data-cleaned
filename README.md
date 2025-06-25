# Data Cleaning of Open Source Mental Illness 2014 Tech Survey

## About:
This dataset is from a 2014 survey that measures attitudes towards mental health and frequency of mental health disorders in the tech workplace. The data can be found here:
https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey

The data was cleaned using python's pandas library. The columns 'Gender' and 'Age' were the one's that were mostly altered. The 'Gender' column was standardized while also not altering good faith or self-described gender identities. The age column had some outlier values that were turned into NaN objects. 1 row was removed for being a response that was either spam or lacked seriousness.

## Data Description:
index
Timestamp
Age
Gender
Country
state: If you live in the United States, which state or territory do you live in?
self_employed: Are you self-employed?
family_history: Do you have a family history of mental illness?
treatment: Have you sought treatment for a mental health condition?
work_interfere: If you have a mental health condition, do you feel that it interferes with your work?
no_employees: How many employees does your company or organization have?
remote_work: Do you work remotely (outside of an office) at least 50% of the time?
tech_company: Is your employer primarily a tech company/organization?
benefits: Does your employer provide mental health benefits?
care_options: Do you know the options for mental health care your employer provides?
wellness_program: Has your employer ever discussed mental health as part of an employee wellness program?
seek_help: Does your employer provide resources to learn more about mental health issues and how to seek help?
anonymity: Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?
leave: How easy is it for you to take medical leave for a mental health condition?
mental_health_consequence: Do you think that discussing a mental health issue with your employer would have negative consequences?
phys_health_consequence: Do you think that discussing a physical health issue with your employer would have negative consequences?
coworkers: Would you be willing to discuss a mental health issue with your coworkers?
supervisor: Would you be willing to discuss a mental health issue with your direct supervisor(s)?
mental_health_interview: Would you bring up a mental health issue with a potential employer in an interview?
phys_health_interview: Would you bring up a physical health issue with a potential employer in an interview?
mental_vs_physical: Do you feel that your employer takes mental health as seriously as physical health?
obs_consequence: Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?
comments: Any additional notes or comments
