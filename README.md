# numbers
DRAFT ONLY

A script for scraping the previous numbers page at Powerball and provides a statistics table on the frequency of each number.
Thought for 6s### Powerball Number Frequency Analyzer

Created a web scraper that fetches Powerball results, analyzes the frequency of each number, and displays the statistics in a table.

## How It Works

Created a Powerball number frequency analyzer with two ways to use it:

1. **Web Application**: A Next.js app with a user interface that displays the frequency statistics in a tabular format with visual indicators.
2. **Command-Line Script**: A Node.js script that you can run directly to get the analysis results in your terminal.


### Features

- Scrapes the Powerball website to get the latest drawing results
- Analyzes both white balls (1-69) and Powerballs (1-26)
- Calculates occurrence count and percentage for each number
- Sorts numbers by frequency
- Displays results in an interactive UI with tabs for white balls and Powerballs
- Includes a progress visualization for each number's frequency


### How to Use

#### Web Application

1. Start the development server: `npm run dev`
2. Open your browser to `http://localhost:3000`
3. View the statistics in the tabular interface
4. Toggle between white balls and Powerballs using the tabs
5. Click "Refresh Data" to fetch the latest results


#### Command-Line Script

Run the script directly to see the results in your terminal:

```plaintext
npm run analyze
```

The script will output:

- Top 10 most frequent white balls
- Top 10 most frequent Powerballs
- 10 least common white balls
- 10 least common Powerballs


 Run analyze-powerball.js
