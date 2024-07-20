# Rapid Incident Locator

The Rapid Incident Locator is a versatile Microsoft Sentinel workbook designed to enhance your incident response and threat hunting capabilities. This workbook is particularly useful in unprecedented situations where you have limited context or a single string/indicator of compromise (IOC) to start with. It helps you quickly identify and locate relevant logs across multiple data tables.

## Features

- **Search Across Multiple Tables:** Input a search string and select a timeframe to get a list of tables where the string matches.
- **Detailed Log Analysis:** Select a table from the list to view matching raw logs in another panel.
- **Customizable Time Range:** Easily adjust the timeframe for your search to focus on recent or historical data.
- **Export Capabilities:** Export results to Excel for further analysis and reporting.

## Usage

1. **Input Parameters:**
   - **SearchString:** Enter the keyword or string you want to search for across the logs.
   - **TimeRange:** Select the desired timeframe for your search.

2. **Run the Workbook:**
   - The workbook will display a list of tables where the search string matches.
   - Select a table name to view the corresponding raw logs in detail.

## Installation

1. Download the `RapidIncidentLocator.json` file from this repository.
2. Open your Microsoft Sentinel instance.
3. Navigate to "Workbooks" and select "Add workbook."
4. Import the downloaded JSON file to create the Rapid Incident Locator workbook.

## Example Use Case

Imagine an incident involving a phishing email. You can input the domain or URL found in the phishing email as the search string. The workbook will help you identify which logs contain this domain or URL and allow you to view detailed logs to understand the extent of the impact and take appropriate action.

## Contributing

We welcome contributions to improve the Rapid Incident Locator workbook. If you have suggestions for new features or enhancements, please open an issue or submit a pull request.

## Author

Created by Rishi Aggarwal.

## Contact

For any questions or support, please open an issue in this repository.
