# Customer-Analytics-Preparing-Data-for-Modeling

## Project Overview
A common problem when creating models to generate business value from data is that the datasets can be so large that it can take days for the model to generate predictions. Ensuring that your dataset is stored as efficiently as possible is crucial for allowing these models to run on a more reasonable timescale without having to reduce the size of the dataset.

## Dataset Information
The dataset consists of anonymized student records, which will be used to predict job-seeking behavior. Each row represents a student, with various features detailing their demographics, education, and professional background.

### Data Columns

| Column                  | Description                                                                          |
|-------------------------|--------------------------------------------------------------------------------------|
| `student_id`             | A unique ID for each student.                                                        |
| `city`                   | A code representing the city the student lives in.                                   |
| `city_development_index` | A scaled development index for the city.                                             |
| `gender`                 | The student's gender.                                                                |
| `relevant_experience`    | An indicator of the student's relevant work experience.                              |
| `enrolled_university`    | The type of university course the student is enrolled in (if any).                   |
| `education_level`        | The student's education level.                                                       |
| `major_discipline`       | The student's major educational discipline.                                          |
| `experience`             | The student's total work experience, measured in years.                              |
| `company_size`           | The size of the company where the student is currently employed (number of employees).|
| `last_new_job`           | The number of years between the student's current and previous jobs.                 |
| `training_hours`         | The total number of training hours completed by the student.                         |
| `job_change`             | Whether the student is looking for a new job (`1` if yes, `0` if no).                |

## Objectives
1. **Data Cleaning**: Ensure that the dataset is free from inconsistencies, missing values, and any irrelevant information.
2. **Efficient Storage**: Propose and implement a more efficient storage solution to allow faster processing of the dataset.
3. **Proof of Concept**: Provide a proof-of-concept that demonstrates the improvements in storage and efficiency.

## Tools and Technologies
- **Python** for data analysis and processing
- **Pandas** for data manipulation and cleaning
- **SQL** or **HDF5** (or other formats) for efficient data storage
- **Jupyter Notebook** for documenting and presenting the work

## How to Use
1. Clone the repository or download the project files.
2. Ensure you have Python 3.x installed.
3. Install the required packages using the following command:
   ```bash
   pip install -r requirements.txt
4. Open the Jupyter notebook or Python script and follow the steps for cleaning and optimizing the dataset.

## Conclusion
By cleaning and optimizing the dataset, we aim to create a proof-of-concept that shows how the customer data can be stored more efficiently while maintaining the integrity of the information.
