Data Analysis & Visualization Program
A command-line interface (CLI) Python application designed to streamline the process of loading, exploring, cleaning, and visualizing tabular datasets using Pandas, NumPy, Matplotlib, and Seaborn.

🚀 Features
Dataset Loading: Seamlessly load any standard CSV dataset with error handling for missing files.

Data Exploration: Instantly view dataframe shapes, head/tail rows, column names, data types, and structural info.

Data Cleaning: Multiple options to handle missing (NaN) values, including viewing null rows, dropping them, or imputing them (via column mean or custom values).

Descriptive Statistics: Generate instant summaries detailing means, medians, standard deviations, and percentiles.

Data Visualization: Built-in plotting capabilities (such as Scatter Plots) with highly customized rendering.

Export Assets: Save your generated charts directly to your local machine with high-resolution (300 DPI) output.

🛠️ Prerequisites & Dependencies
Before running the script, ensure you have Python 3.x installed along with the required library dependencies:

Bash
pip install pandas numpy matplotlib seaborn
💻 How to Use
Clone or Download the repository and navigate to the project directory.

Run the application from your terminal:

Bash
python project9.py
Use the interactive on-screen menu to navigate the application functions by entering the corresponding number (1-8).

Interactive Menu Overview:
Plaintext
========== Data Analysis & Visualization Program ==========
1. Load Dataset
2. Explore Data
3. Perform DataFrame Operations
4. Handle Missing Data
5. Generate Descriptive Statistics
6. Data Visualization
7. Save Visualization
8. Exit
==========================================================
📂 Project Structure
project9.py: The core application file containing the SalesDataAnalyzer engine class and the interactive execution loop.

README.md: Project documentation and user guide.

📝 Future Roadmap / TODOs
[ ] Complete functional implementation for option 3 (DataFrame aggregations/mathematical operations).

[ ] Expand data visualization options to fully implement Bar, Line, Pie, Histogram, and Stack plots.

[ ] Add support for Excel (.xlsx) and JSON data files.

📄 License
