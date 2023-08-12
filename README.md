# Data-Wrangling-Hotel

### Business Task
- To keep important columns and drop redundant columns.
- To change the datatypes of attributes to proper datatypes.
- To deal with missing values

### Data Set
- From Kaggle. View [Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand?resource=download).

### Tools
- Jupyter Notebook for data analysis using Python - View [Python code](https://github.com/sanjanand06/Data-Wrangling-Hotel/blob/main/Data-Wrangling-Hotel-Booking.ipynb)

### Outcome
- Converted datatype of “reservation_status_date” from object to DateTime
- Created a new column to combine year, month, and day.
- Attributes such as "company", "agent", "country" and "children" have missing values.                            
- Since the missing values in the "children" attribute are 4, they are replaced by the mean.
- "Company" attribute is completely dropped since it has the highest number of missing values, almost 70% of values are missing.
  

