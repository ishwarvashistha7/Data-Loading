# Data-Loading
Pandas me Data Load, Save aur Import options sikhne ka basic notebook hai!
# 📊 Data Loading & Data Storage in Pandas
A comprehensive guide and practical walkthrough on data ingestion, inspection, and export techniques using Python's **Pandas** library. This project covers reading and writing data across various file formats along with essential parameters for data manipulation during load time.

## 📌 Key Features & Topics Covered
### 1. 📂 File Formats Supported
- **CSV (`.csv`)**: Reading and writing comma-separated value files.
- **Excel (`.xlsx`)**: Exporting DataFrames with custom sheet names (`sheet_name`) and reading them back using `openpyxl`.
- **JSON (`.json`)**: Handling structured JSON data with record orientation (`orient='records'`) and formatting (`indent=4`).
- **TSV (`.tsv`)**: Working with tab-separated text files using custom delimiters (`sep='\t'`).
- **FWF (`.fwf`)**: Formatting, creating, and reading Fixed-Width Format text files using `read_fwf`.
### 2. 🔍 Data Inspection Techniques
Quick structural inspection of loaded DataFrames using core Pandas functions and attributes:
- **`shape` & `size`**: Inspecting matrix dimensions (rows, columns) and total element count.
- **`columns` & `dtypes`**: Reviewing column identifiers and data types.
- **`head()` & `tail()`**: Previewing top and bottom rows of a dataset.
### 3. ⚙️ Essential `read_csv()` Parameters
Demonstrating practical data handling techniques using specific parameter configurations:
- **`sep`**: Defining custom delimiters (e.g., `,`, `\t`).
- **`nrows`**: Reading a specific number of rows for testing large datasets.
- **`usecols`**: Selectively loading required columns to optimize memory usage.
- **`index_col`**: Setting existing dataset columns as DataFrame indices during ingestion.
- **`skiprows`**: Skipping unwanted metadata or header lines.
- **`header`**: Managing datasets without column titles or assigning header levels
## 🛠️ Prerequisites & Installation
Ensure you have Python installed along with the required dependencies:

```bash
pip install pandas openpyxl
