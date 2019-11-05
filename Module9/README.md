## Haris Sumra
## Community Health Survery Analysis
## 11/03/2019

### In this Project:
* Usin pandas to ingest and select data for analysis.
* Clean up the data; drop any unnecessary columns along with renaming the columns. 
* Make a slice of the data that keeps just the "Year", "Question" and "Prevalence" columns.
* The data is in long format. Make it into a wide format: First, make the question text the column header, and the year the row index. Next, make the year the column header, and the question text the row index.
* Data was collected from (https://data.cityofnewyork.us/resource/2r9r-m6j4.csv)

### Conclussion: I prefer wide format, it helps aggregate data so it is easily readable. For instance, you can pin-point the question on each year scale without going through a lot of rows. So, wide format is good for looking at specific questions asked in a given year but if you want to apply the statistical analysis then long format would be a better choice because it helps you see your data in a bigger picture like get the mean value by each year. If I was working on this project, I would group the question column by specific type to narrow down the data itself. 
