# Wine Quality Analysis (Excel)

## Project Summary
An analysis of 1,599 red wine samples to find which lab measurements go with higher quality scores. This is a quality control style analysis built in Excel.

## Dataset
Red Wine Quality dataset from the UCI Machine Learning Repository. It has 11 lab measurements (such as alcohol, volatile acidity and sulphates) and a quality score for each sample.

## Method
- Split the raw CSV into columns (Text to Columns)
- Grouped quality scores with an IF formula: High (7 or more), Medium (5 to 6), Low (below 5)
- Calculated counts and averages with COUNTIF and AVERAGEIFS
- Built a PivotTable comparing the three groups
- Created two charts: samples per group and average alcohol per group

## Key Findings
- Most samples are Medium (1,319 samples, about 82%). High has 217 (about 14%) and Low has 63 (about 4%).
- High-quality wines have the highest average alcohol (about 11.5%), against about 10.2% for Low and Medium.
- High-quality wines have the lowest volatile acidity (about 0.4), against about 0.7 for Low-quality wines.
- High-quality wines have slightly higher sulphates (about 0.7) than the other groups (about 0.6).

## Conclusion
Higher alcohol and lower volatile acidity go with better wine quality.

## Files
- wine_quality_analysis.xlsx: the full workbook with data, analysis and charts
- wine_quality_excel_report.pdf: a short report with the findings and charts

## Tools
Microsoft Excel (Text to Columns, IF, COUNTIF, AVERAGEIFS, PivotTables, charts)
