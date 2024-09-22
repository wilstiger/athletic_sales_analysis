
# Athletic Sales Analysis

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Conclusion](#conclusion)

## Installation

To set up the project on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/athletic_sales_analysis.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd athletic_sales_analysis
   ```

3. **Create and activate a virtual environment**:
   ```bash
   python -m venv env
   source env/bin/activate    # On macOS/Linux
   env\Scripts\activate     # On Windows
   ```

4. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run the analysis in the `athletic_sales_analysis.ipynb` notebook.

Explore the results of the analysis, which include:
- The top 5 regions, states, and cities that sold the most athletic wear.
- Retailers with the greatest total sales.
- Insights into women's athletic footwear sales by day and week.

## Technologies Used

- **Python**: Primary language for the analysis.
- **Pandas**: For data manipulation and analysis.
- **Jupyter Notebook**: To create and run the analysis interactively.
- **Matplotlib/Seaborn**: Optional, for data visualization.

## File Structure

```bash
athletic_sales_analysis/
│
├── athletic_sales_analysis.ipynb  # Main notebook with all analysis steps
├── athletic_sales_2020.csv        # Sales data for 2020
├── athletic_sales_2021.csv        # Sales data for 2021
├── README.md                      # This file
└── requirements.txt               # List of dependencies
```

## Conclusion

This project successfully provides insights into athletic wear sales data, focusing on total product sales, top regions, and retailer performance. Detailed analysis of women's athletic footwear sales by day and week also adds significant value. The use of Python and Pandas enables efficient data manipulation, while Jupyter Notebook offers an interactive way to conduct the analysis.
