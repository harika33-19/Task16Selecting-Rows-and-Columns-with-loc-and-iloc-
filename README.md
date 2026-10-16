# Task16Selecting-Rows-and-Columns-with-loc-and-iloc

## Description
This project demonstrates how to select rows and columns from a Pandas DataFrame using `loc[]` (label-based selection) and `iloc[]` (integer position-based selection).

## Objective
Develop accurate DataFrame selection skills and understand the difference between `loc[]` and `iloc[]`.

## Tools Used
- Python
- Pandas
- Google Colab / Jupyter Notebook

## Dataset
A small sample dataset of five students is created directly in Python.

| Name | Age | Marks |
|---|---:|---:|
| Ravi | 18 | 85 |
| Priya | 19 | 92 |
| Rahul | 18 | 78 |
| Sneha | 20 | 95 |
| Arjun | 19 | 88 |

## Examples Covered

### `loc[]` â€” Label-Based Selection
1. Select a row by its label.
2. Select the `Name` column.
3. Select a single value: Priya's marks.
4. Select rows with labels 1 through 3.
5. Select the `Name` and `Marks` columns for selected rows.

### `iloc[]` â€” Position-Based Selection
1. Select a row by its integer position.
2. Select the first column by position.
3. Select a single value by row and column positions.
4. Select positions 1 through 3 (the ending position is excluded).
5. Select the first three rows and the first and third columns.

## Key Difference

| Feature | `loc[]` | `iloc[]` |
|---|---|---|
| Selection | Labels | Integer positions |
| Example | `df.loc[1, "Marks"]` | `df.iloc[1, 2]` |
| Slice ending | Included | Excluded |

## How to Run
1. Open Google Colab or Jupyter Notebook.
2. Create a new Python notebook.
3. Copy the code from the task notebook into a cell.
4. Run the cell and review each output.

## Conclusion
`loc[]` is useful when selecting data by row or column labels, while `iloc[]` is useful when selecting data by integer positions. Both methods are essential for working efficiently with Pandas DataFrames.
