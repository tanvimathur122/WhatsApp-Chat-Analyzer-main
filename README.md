# WhatsApp Chat Analyzer

This project is a comprehensive tool for analyzing WhatsApp chat histories. It uses Python and Streamlit to visualize chat data, providing insights into messaging patterns and media sharing habits.

## Prerequisites

Before running this application, ensure you have Python installed on your system. Install all necessary libraries using the command below:

```bash
pip install -r requirements.txt
```

## Features

- Upload and analyze WhatsApp chat files.
- Visualize statistics such as total messages, words, media shared, and links.
- Generate monthly and daily activity timelines.
- Display activity maps for days of the week and months.
- Create word clouds and conduct emoji analysis.
- Identify the most active users in group chats.

## How to Use

1. Run the Streamlit app by executing the following command in your terminal:
```bash
streamlit run app.py
```
2. Upload your WhatsApp chat file through the sidebar.
3. Select a user to analyze or choose “Overall” for group-wide statistics.
4. Click “Show Analysis” to view various visualizations and statistics.

## File Structure

- app.py: The main Streamlit application script.
- preprocessor.py: Contains functions for preprocessing chat data.
- helper.py: Includes functions for generating statistics and visualizations.
- requirements.txt: Specifies the required libraries.

## Usage Notes

- The application is designed to work with exported WhatsApp chat files.
- Ensure the chat file is in the correct format as exported directly from WhatsApp.
