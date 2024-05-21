# PowerBIConversionUtility

This utility simplifies the process of converting reports from one reporting tool to another. Using built-in AI functionality, it extracts metadata from the selected source file and converts it into structures compatible with the target format. It extracts functions and metadata from workbooks, transforms them into Power BI-compatible structures, and generates Power BI-compatible files. This enables organizations to smoothly convert their dashboards to Power BI, saving time and resources.

## Features

- Intelligent mapping of visualizations, data sources, and configurations to Power BI equivalents.
- Customizable features to tailor the migration process to specific requirements.
- Automation of the dashboard migration process.
- Comprehensive support and documentation for a seamless transition.

## Prerequisites

- Python 3.7 or higher
- Flask Module
- Pandas Module
- xml.etree.ElementTree Module
- Tableau Hyper API Module
- Report Lab Module
- Access to Spotfire server repository
- Access to Spotfire Library

## Setup

1. Ensure you have Python 3.7 or higher installed on your system.
2. Install the required Python packages using pip:

    ```bash
    pip install Flask
    pip install pandas
    pip install reportlab
    pip install tableauhyperapi
    ```

## Running the Script

1. Save the script as `app.py`.
2. Run the script using
