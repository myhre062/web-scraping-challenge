# web-scraping-challenge

# Module 12

This project involves web scraping data related to Mars from various sources. The goal is to gather information about Mars and analyze it.

## Part 1: Mars News Scraping

### Notebook: part_1_mars_news.ipynb

#### Objective:
Scrape titles and preview text from a Mars news website.

#### Steps:
1. Use automated browsing to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html).
2. Extract text elements from the website using BeautifulSoup.
3. Store the titles and preview text of the news articles in Python data structures.
4. Print the list of dictionaries containing the scraped data.

## Part 2: Mars Weather Data Scraping and Analysis

### Notebook: part_2_mars_weather.ipynb

#### Objective:
Scrape and analyze Mars weather data from a website.

#### Steps:
1. Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
2. Scrape the data from the HTML table using BeautifulSoup.
3. Store the scraped data in a Pandas DataFrame and prepare it for analysis.
4. Analyze the dataset by answering questions such as the number of months on Mars, the number of Martian days' worth of data, average low temperature by month, etc.
5. Visualize the analysis results using matplotlib.
6. Export the DataFrame to a CSV file for further use.

## Data Files:

1. **mars_data.csv**: Contains scraped Mars weather data stored in a CSV format.

## Setup:

1. Clone this repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter notebooks to execute the web scraping and analysis tasks.

