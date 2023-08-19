# Audible Library to Goodreads Importer

This repository contains a script that allows you to download your Audible library from the library page on your account and then import it to Goodreads. This can be especially useful if you want to keep track of your audiobooks in both platforms.

## Prerequisites

Before using the script, make sure you have the following:

1. **Google Chrome Browser**: This script is designed to be used in the Google Chrome browser, so please ensure you have it installed.

## Usage

Follow these steps to use the script and import your Audible library to Goodreads:

1. **Download the Script**: Copy the code from the [`audible_to_goodreads.js`](audible_to_goodreads.js) file in this repository.

2. **Open Chrome Development Console**: Open your Google Chrome browser and navigate to the Audible library page on your account.

3. **Access Developer Console**: To access the developer console, you can usually right-click anywhere on the page, select "Inspect" or "Inspect Element," and then navigate to the "Console" tab.

4. **Paste and Execute the Script**: In the console, paste the code you copied from the `audible_to_goodreads.js` file and press Enter. The script will start fetching data from your Audible library and display the output in the console.

5. **Save Console Output as JSON**: Copy the output from the console and save it as a JSON file on your local machine. This JSON file contains your Audible library data.

6. **Reformat JSON to XLS**: You need to convert the JSON file to an XLS (Excel) format. You can use various online tools or software to accomplish this. The JSON data should be converted into a tabular format that matches the template provided in the [Goodreads Sample Export CSV](https://www.goodreads.com/assets/sample_export.csv).

7. **Edit XLS File**: Open the XLS file in a spreadsheet editor (like Microsoft Excel or Google Sheets) and edit the data according to the template provided in the [Goodreads Sample Export CSV](https://www.goodreads.com/assets/sample_export.csv).

8. **Import to Goodreads**: Go to the [Goodreads Import Page](https://www.goodreads.com/review/import) and follow the instructions to import your edited XLS file. This will add your Audible library data to your Goodreads account.

## Disclaimer

Please note that using scripts to interact with websites and services might violate their terms of service. Use this script responsibly and only for personal use. The authors of this script are not responsible for any misuse or unintended consequences.

## Contributing

If you find any issues with the script or have suggestions for improvements, feel free to open an issue or submit a pull request in this repository.
