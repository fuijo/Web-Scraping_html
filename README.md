This project involved scraping and analyzing data from two Mars-related sources to deepen web-scraping skills and provide meaningful insights about Martian news and weather conditions. The project consisted of two main deliverables: scraping Mars news articles and analyzing Mars weather data.

**Deliverable 1:** Scrape Titles and Preview Text from Mars News
**Objective:** Extract the latest news titles and previews from the Mars News website.

**Automated Browsing:**

Used Splinter to automate browsing and access the Mars News website.
Extracted HTML elements using Beautiful Soup for further analysis.

**Data Extraction:**

Scraped the titles and preview text of the news articles.
Stored the data in a Python list of dictionaries, with each dictionary containing:
Title: The headline of the article.
Preview: A brief summary of the article.

**Optional Output:**

Saved the extracted data to a JSON file for easy sharing.
Outcome: Successfully scraped and stored Mars news titles and previews, enabling further analysis or publication.

**Deliverable 2:** Scrape and Analyze Mars Weather Data
Objective: Extract and analyze weather data from an HTML table on the Mars Temperature Data site.

**Data Scraping:**

Used Beautiful Soup to parse the HTML table and extract the weather data.
Constructed a Pandas DataFrame with the following columns:
id, terrestrial_date, sol, ls, month, min_temp, and pressure.

**Data Cleaning:**

Converted columns to appropriate data types (e.g., datetime, float, integer) for analysis.

**Data Analysis:**

**Answered the following questions:**
**Number of Mars Months:**
Identified 12 distinct months on Mars.

**Number of Martian Days:**
Found that the dataset contained data for several Martian sols.

**Temperature Trends:**
Calculated average minimum temperatures for each month.
Identified the coldest and warmest months and visualized the results using a bar chart.

**Atmospheric Pressure Trends:**
Calculated average atmospheric pressure for each month.
Determined the months with the lowest and highest pressure, supported by a bar chart.

**Martian Year Duration:**
Estimated the duration of a Martian year in terrestrial days by analyzing temperature cycles and visualizing the daily minimum temperatures.

**Data Export:**

Saved the cleaned and analyzed DataFrame to a CSV file for further use.
**Outcome:** Delivered a comprehensive analysis of Martian weather patterns, supported by visualizations and a structured dataset.

Key Insights
Mars News:
Extracted up-to-date news titles and summaries, providing a foundation for public engagement or scientific reporting.
Mars Weather:
Identified critical environmental trends on Mars, including temperature and pressure variations.
Estimated the duration of a Martian year, highlighting seasonal changes.
