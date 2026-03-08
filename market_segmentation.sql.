-- Analysis: Targeted Data Analyst Salary Audit
-- Progress: Using SELECT, WHERE, AND, IN, BETWEEN, and ORDER BY
-- Purpose: Filtering for Data Analysts in specific hubs within a set salary range.

SELECT 
    job_title_short, 
    job_location, 
    salary_year_avg
FROM 
    job_postings_fact
WHERE 
    job_title_short = 'Data Analyst'
    AND job_location IN ('Anywhere', 'New York, NY', 'California', 'Texas')
    AND salary_year_avg BETWEEN 80000 AND 150000
ORDER BY 
    salary_year_avg DESC;
