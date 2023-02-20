# Skill_Indexer_HR

## "Resume Matchmaker: A Skills Scraping and Job Matching Tool"

This project aims to scrape the skills listed on resumes and match them to job roles to identify how many skills a candidate has that are suitable for a particular job. The project involves the use of natural language processing (NLP) techniques to extract the skills from resumes and match them to job roles.

The project uses the following formula to calculate score: 

```
score = 2*len(skills_matched_from_database) + num_common_bigrams + num_common_trigrams
```

### To use the tool

1. Run the UI.py file.
2. Enter the JD for the role
3. Browse to the folder containing the resume
4. Click on Calculate Score

### The project includes the following features:

1. Scraping skills from resumes
2. Storing the scraped data in a database
3. Matching the skills to job roles
4. Providing a user-friendly interface for searching and matching skills to job roles
5. Calculate and rank the candidates based on the profile matching with the JD.

### This Project can be useful for:

1. Recruiters and hiring managers who want to quickly identify which candidates have the skills needed for a particular job
2. Job seekers who want to see which jobs they are best suited for based on their skills
3. Human resource professionals who want to improve their recruitment process

Overall, "Resume Matchmaker: A Skills Scraping and Job Matching Tool" is a project that can help to identify the best match of skills between candidate and job role, providing a streamlined and efficient recruitment process.
