# Atlassian Case Study: Improving Sprint Efficiency

## Overview
This project analyzes simulated Jira-style ticket data to identify inefficiencies in sprint performance, ticket resolution, and workload distribution. The goal is to generate data-driven recommendations that could help improve engineering productivity and sprint execution.

## Business Questions
- Which tickets take the longest to resolve?
- Do reopened tickets increase cycle time?
- Are some assignees overloaded?
- Are some teams slower than others?

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Key Insights
- High-priority tickets had longer average cycle times
- Reopened tickets were associated with longer resolution times
- Workload distribution across assignees was uneven
- Some teams had higher average cycle times than others

## Recommendations
- Use workload-aware ticket assignment
- Improve ticket requirements and QA processes
- Monitor team-level cycle times for bottlenecks
- Use data to improve sprint planning

## Project Structure
- `notebooks/` → analysis notebook
- `data/` → simulated dataset
- `images/` → charts and screenshots
- `dashboard/` → Power BI dashboard file
