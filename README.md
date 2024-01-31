# Homework2_zoomcamp



## Question 1. Data Loading

Once the dataset is loaded, what's the shape of the data?

* 266,855 rows x 20 columns
* 544,898 rows x 18 columns
* 544,898 rows x 20 columns
* 133,744 rows x 20 columns

from the picture we can see the answer is

* 266,855 rows x 20 columns

<img src="https://github.com/juandavidlozano/Homework2_zoomcamp/blob/main/homework2.1.jpg" alt="Answer 1" width="1000" height="900">

## Question 2. Data Transformation

Upon filtering the dataset where the passenger count is greater than 0 _and_ the trip distance is greater than zero, how many rows are left?

* 544,897 rows
* 266,855 rows
* 139,370 rows
* 266,856 rows


from the picture we can see the answer is

* 139,370 rows

<img src="https://github.com/juandavidlozano/Homework2_zoomcamp/blob/main/homework2.2.jpg" alt="Answer 1" width="1000" height="900">


## Question 3. Data Transformation

Which of the following creates a new column `lpep_pickup_date` by converting `lpep_pickup_datetime` to a date?

* `data = data['lpep_pickup_datetime'].date`
* `data('lpep_pickup_date') = data['lpep_pickup_datetime'].date`
* `data['lpep_pickup_date'] = data['lpep_pickup_datetime'].dt.date`
* `data['lpep_pickup_date'] = data['lpep_pickup_datetime'].dt().date()`

from the picture we can see the answer is

* `data['lpep_pickup_date'] = data['lpep_pickup_datetime'].dt.date`


<img src="https://github.com/juandavidlozano/Homework2_zoomcamp/blob/main/homework2.3.jpg" alt="Answer 1" width="1000" height="900">



## Question 4. Data Transformation

What are the existing values of `VendorID` in the dataset?

* 1, 2, or 3
* 1 or 2
* 1, 2, 3, 4
* 1

so I added a print statement to give me answers

from the picture we can see the answer is 

* 1 or 2

<img src="https://github.com/juandavidlozano/Homework2_zoomcamp/blob/main/homework2.4.jpg" alt="Answer 1" width="1000" height="900">


## Question 5. Data Transformation

How many columns need to be renamed to snake case?

* 3
* 6
* 2
* 4


so I added a print statement to give me answers

from the picture we can see the answer is

* 4

<img src="https://github.com/juandavidlozano/Homework2_zoomcamp/blob/main/homework2.4.jpg" alt="Answer 1" width="1000" height="900">



## Question 6. Data Exporting

Once exported, how many partitions (folders) are present in Google Cloud?

* 96
* 56
* 67
* 108


from the picture we can see the closest answer is

* 96

  <img src="https://github.com/juandavidlozano/Homework2_zoomcamp/blob/main/homework2.5.jpg" alt="Answer 1" width="500" height="900">






