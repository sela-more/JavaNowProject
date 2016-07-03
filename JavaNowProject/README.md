# JavaNowProject
Candidate management system

In this project we will develop candidate management system for recruiting developers. The system will provide API for creating job description, getting CV in several formats. Managing the recruitment process and loading machines that will include tests for the candidates.

The system will be developed in micro services architecture and will be deployed on Google cloud. Here are the micro services that will implement the system:
1. Send CV as text (WORD, PDF) – API for getting CV in different formats, WORD, PDF and text and save them in the system, the CV should be in format that can be parsed by other micro services.

2. Create job description – provide API for the companies to add job description for his company, the job descriptions will be stored in the system and it will be used to match CV.

3. Match CV to job description
This micro service will try to match the best CV according to advance algorithms to find the right candidate for the company. 

4. Schedule an interview – Scheduling an interview to the candidate and trigger the recruitment process

5. Load machine module – a micro service that automatically load and unload machines for testing so the candidate will be able to write code that will be tested by the company.

6. Job interview template
Enable each company to write their own template of what should be asked in the interview and what is the impression and who should be interviewed. 

7. Job interview – filling up the form about the candidate

8. Reports for companies – writing a dashboard about candidates, candidates in process and candidates that recruited in the system \

9. User dashboard – to which companies the user applied and what is the status and each one of them

The system will be written in Google app engine and Google container engine. With micro service architecture and usage of: Google cloud storage, datastore, task queue, compute engine and big query. We may use cloud SQL and data proc as well. 
Micro services will be written in spring or without spring using REST API mostly.
