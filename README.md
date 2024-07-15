# Data Cleaning and Analysis Exercise Using Python

### Overview
A DA Exercise that aims to clean and analyze user application data based on a established criteria. This exercise focused on various libraries such as pandas and numpy for data cleaning and matplotlib for chart representation of the analysis.

### Steps

I. Review the dataset

- Application data

![app_csv_output_data](https://github.com/user-attachments/assets/ede4c47a-ee50-4f8e-87f6-15b7c99f414f)

- Industry data

![ind_csv_output_data](https://github.com/user-attachments/assets/82968b9c-3b22-476d-b1d9-f006179e1ea6)

II. Data Cleaning
- Removing Duplicates
- Filling missing values

&nbsp;&nbsp;Code Snippet:

![Task 1](https://github.com/user-attachments/assets/9a0f8a38-650c-49b5-9e5d-8b02eaeffc7c)

&nbsp;&nbsp;Output:

![Task 1 Output](https://github.com/user-attachments/assets/960aee55-8861-43cf-b55a-77f85e6d8bc6)


III. Merging of Data
- Merge Industry data with Application data

&nbsp;&nbsp;Code Snippet:

![Task 2](https://github.com/user-attachments/assets/8e0baecf-2a56-4970-9475-50ea3f260aae)

&nbsp;&nbsp;Output:

![Task 2 Output](https://github.com/user-attachments/assets/2b6df9aa-b3a9-4837-98d9-696b9eca95e9)

IV. Rating Each Application

Each application will be rated based on the following criteria and will be translated into code to compute the total rating.

- If the applicant's age is between 35 and 55, 20 points are added to the rating
- If the application was submitted on a weekend, 20 points are added to the rating
- If the applicant is married, 20 points are added to the rating
- If the applicant is located in Kyiv or the region, 10 points are added to the rating
- The Score value from the industries.csv table is also added to the application (and ranges from 0 to 20 points)
- If External Rating is greater than or equal to 7, 20 points are added to the rating
- If External Rating is less than or equal to 2, 20 points are deducted from the rating

&nbsp;&nbsp;Code Snippet:

![Task 3](https://github.com/user-attachments/assets/5f50b610-c078-4361-afdf-860299c14693)

&nbsp;&nbsp;Output:

![Task 3 Output](https://github.com/user-attachments/assets/cba5c3d8-f08e-461d-97c9-5d23a0accd4b)


V. Filtering Accepted Application
Applications with a rating greater than zero are considered as accepted.

&nbsp;&nbsp;Code Snippet:

![Task 4](https://github.com/user-attachments/assets/79694f65-6e3f-46d1-9d3a-fdf87ee09d06)

&nbsp;&nbsp;Output:

![Task 4 Output](https://github.com/user-attachments/assets/1a01c3a7-954e-453a-a114-2613b7b3cb7b)


VI. Analysis of Accepted Applicants
Lastly, the average rating for accpeted applicants were analyzed and plotted.

&nbsp;&nbsp;Code Snippet:

![Task 5](https://github.com/user-attachments/assets/907edb94-440e-4662-a26d-527b14dbd98a)

&nbsp;&nbsp;Output:

![Task 5 Output](https://github.com/user-attachments/assets/aff1211a-78dc-43fa-bcf0-c1944047df3f)

Click here for the [Documentation](https://colab.research.google.com/drive/1hnI9-l_qK7YiLz_J9E-PCcn7UMfZZaPx?usp=sharing) to see the complete details.

### Conclusion

 <p align="justify">The first week has the highest score of 40 but declined as it reached the last week with the lowest data of about 32. Overall the data presented was in decline, with it having some upward movements but never did broke the highest score and continued in dicline until the end. This shows that as weeks go by it gets harder and harder for the applicants to comply with the given criteria.</p>

### Data Source

Both Application and Industry data were provided by GoIT as part of its course work.

### Tools

For this exercise, Google Colab was used for Python coding.

### Files
- Google Colab: Contains all the steps and details done in completing the exercise.
- Dataset: Contains the data files used for this exercise.

[[Files]](https://drive.google.com/drive/folders/1nDYGNW-v5EjVA-hViunINZ1_OfqFBD4W?usp=sharing)

