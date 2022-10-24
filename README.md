## What is in this dataset?
The number of customers in arrears for longer than 60 days and dollar amount of arrears, reported by regulated utility companies in New York State.

## How is the data collected and published?
- Data Source: [New York State Department of Public Service](https://documents.dps.ny.gov/public/MatterManagement/CaseMaster.aspx?MatterSeq=1331&MNO=91-M-0744)
- The original reports were either in excel and pdf formats, deferring by month and company. Reports in excel format were automatically read and processed as a database. Reports in pdf format were reviewed manually and were combined with the excel reports to complete the database.

## Data dictionary

| Variable | Description |
| ----------- | ----------- |
| utility | Name of the utility company, regulated by and reporting to the New York State Department of Public Service. |
| month | The month in which the data is collected |
| arrears_c | Number of customers in arrears |
| arrears_d | Dollars amount in arrears |

- The timeline of dataset ranges from October 2019 through July 2022.
