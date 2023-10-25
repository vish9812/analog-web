# Analog

Analog is a powerful tool designed for analyzing and visualizing log files. It provides several features to help you efficiently work with your log data. Whether you need to identify common patterns, compare logs from different versions of your application, or filter logs based on various criteria, this app has you covered.

## Features

- **Top Logs**: Quickly identify and analyze the most frequently occurring log entries.

- **Filter Logs**:

  - **Filter by Timestamp**: Specify a start and end timestamp to narrow down your log analysis.
  - **Regex Search**: Perform regular expression searches to find specific log entries.
  - **Top Logs**: Select entries in the Top Logs to view all the related logs together.
  - **Errors Only**: Isolate and focus on error log entries.

- **Log File Comparison**:
  - **Compare Two Log Files**: Compare two log files and see newly added or removed log entries.
- **Create and Download a Filtered Subset**: Define filtering criteria to extract a specific subset of logs. You can also compare two subsets of a single log file to track changes.

- **Time Jumps**: Navigate through log data in subsets repeating after every few minutes.

- **See Data for Specific Fields/Keys**: Easily access and view log entries based on specific fields.

- **Highlighted JSON Syntax**: Log entries with JSON data are automatically highlighted for improved readability.

- **Highlighted Errors**: Errors in log entries are highlighted, making them stand out for quick identification.

## Things to remember

- Currently supports only `json` logs.
- Ensure you have Python 3 installed on your system to simply run via executing the `analog.sh`.
- Or you can use any server of your preference to run the `index.html`

## Getting Started

Follow these steps to run the app:

1. Download the app from the [Releases Page](https://github.com/vish9812/analog/releases).

2. Unzip the downloaded file to your desired location.

3. Open a terminal and navigate to the app's directory.

4. Execute the `analog.sh` script to start the app:

5. Open your web browser and visit the following URL: `localhost:20002`

You are now ready to use the Analog and take advantage of its powerful log analysis features.

Enjoy analyzing your log data!

## License

This app is released under the [MIT License](https://github.com/vish9812/analog/blob/main/LICENSE).
