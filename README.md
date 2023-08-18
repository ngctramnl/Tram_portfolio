# Data Analyst Portfolio

## [Project 1: Data_Cleaning](https://github.com/ngctramnl/Data_Cleaning) 
### About the dataset
- Originally from [data_description](https://archive.ics.uci.edu/dataset/10/automobile)

### Data Cleaning Documentation
- _DISTINCT_ query was run to confirm fuel_type does not have any unexpected values other than gas and diesel. No unexpected value was returned.
- The range of the length column is supposed to be between 141.1 and 208.1. Query was run to confirm. The results were aligned with the dataset.
- _IS NULL_ Query was run to detect missing values. Two missing values were returned.
- Those 2 missing were filled with the value "four". 5 rows were affected in total.
- Once there are no missing values, _DISTINCT_ query was run to check for potential errors in the num_of_cylinders column.
- There are two entries for two cylinders but the 'two' is misspelled
- _UPDATE_ query was run to correct the misspelling for all rows.
- Next, to check the consistency of the compression_ratio column, _MIN_ and _MAX_ was used. This returned a maximum of 70 is an error because the maximum value in this column should be 23, not 70.
- _COUNT_ was used to check the number of rows with the maximum value of 70. This returned only 1 row.
- _DELETE_ was used to exclude 1 row from the dataset



## [Project 2: Departmental Store Visualization](https://github.com/ngctramnl/Departmental_Store)
- Dataset of a departmental store with details of products from May 2020, a period marked by COVID-19
- Visualize which products will be more profitable to invest in
- Visualize patterns and trends of the product categories
<div class='tableauPlaceholder' id='viz1692194439466' style='position: relative'><noscript><a href='#'><img alt='Dashboard 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DepartmentalStorein2020&#47;Dashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DepartmentalStorein2020&#47;Dashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DepartmentalStorein2020&#47;Dashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>         

## [Project 3: Hotel Bookings](https://github.com/ngctramnl/Hotel_bookings)
- The data is originally from the article [Hotel Booking Demand Datasets](https://www.sciencedirect.com/science/article/pii/S2352340918315191), written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019
- The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020
- Create exploratory plots
- Explore the variance between the hotel stays of guests with/without children among months of the year

  
![alt text](https://github.com/ngctramnl/Hotel_bookings/blob/main/Month.png)
- July and August are the two months that have the most with-children stays. This trend is consistent in both hotels.

![alt text](https://github.com/ngctramnl/Hotel_bookings/blob/main/Parking.png)
- People who are with children are more likely to ask for parking space

![alt text](https://github.com/ngctramnl/Hotel_bookings/blob/main/Boxplot.png)
- People with children tend to spend more on their stays

## [Project 4: Technology Perception](https://github.com/ngctramnl/TechnologyAdoption)
- Dataset collected from a [survey](https://www.kaggle.com/datasets/mrcalvinwhite/technology-perception-survey) primarily conducted in India
- Survey data was collected to measure technology usage patterns, perceived benefits, perceived risks, perceived barriers, likeliness to adopt, likeliness to recommend, etc.
- Identify key factors influencing technology adoptions and recommendation behaviours among consumer households
- Build a multiple regression model





