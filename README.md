# AI-Jobs-Salary-Analysis
AI &amp; Machine Learning Job Market Insights
What's Inside
This dataset provides an extensive analysis of the artificial intelligence job market with over 15,000 real job postings collected from major job platforms worldwide. It includes detailed salary information, job requirements, company insights, and geographic trends.

Key Features:

15,000+ job listings from 50+ countries
Salary data in multiple currencies (normalized to USD)
Experience level categorization (Entry, Mid, Senior, Executive)
Company size impact analysis
Remote work trends and patterns
Skills demand analysis
Geographic salary variations
Time-series data showing market evolution

Columns Description

job_id	Unique identifier for each job posting	String
job_title	Standardized job title	String
salary_usd	Annual salary in USD	Integer
salary_currency	Original salary currency	String
salary_local	Salary in local currency	Float
experience_level	EN (Entry), MI (Mid), SE (Senior), EX (Executive)	String
employment_type	FT (Full-time), PT (Part-time), CT (Contract), FL (Freelance)	String
job_category	ML Engineer, Data Scientist, AI Researcher, etc.	String
company_location	Country where company is located	String
company_size	S (Small <50), M (Medium 50-250), L (Large >250)	String
employee_residence	Country where employee resides	String
remote_ratio	0 (No remote), 50 (Hybrid), 100 (Fully remote)	Integer
required_skills	Top 5 required skills (comma-separated)	String
education_required	Minimum education requirement	String
years_experience	Required years of experience	Integer
industry	Industry sector of the company	String
posting_date	Date when job was posted	Date
application_deadline	Application deadline	Date
job_description_length	Character count of job description	Integer
benefits_score	Numerical score of benefits package (1-10)	Float

Salary Prediction Models

Build ML models to predict AI job salaries
Analyze factors affecting compensation
Compare salaries across different locations
Market Trend Analysis

Track the evolution of AI job market
Identify emerging job roles and skills
Analyze remote work adoption patterns
Career Planning

Understand skill requirements for different positions
Compare opportunities across countries
Plan career progression paths
Business Intelligence

Company hiring patterns analysis
Skills gap identification
Market competition insights
Geographic Studies

Cost of living vs. salary analysis
Regional market maturity assessment
Immigration pattern correlations
Data Collection Methodology

Data was collected through ethical web scraping from major job platforms including:

LinkedIn Jobs
Indeed
Glassdoor
AngelList
Stack Overflow Jobs
Company career pages
