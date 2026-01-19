# BIG-DATA-ANALYSIS

*COMPANY* - CODTECH IT SOLUTIONS PRIVATE LIMITED

*NAME* - VISHNU LAMBA

*INTERN ID* - CTIS2986

*DOMAIN* - DATA ANALYTICS

*DURATION* - 8 WEEKS

*MENTOR* - NEELA SANTOSH

*DESCRIPTION OF THE TASK 1* 

My project focuses on performing large-scale data analysis on Delhi Metro datasets using the python library - Dask. The objective of the task is to analyze the real-world transportation data, to extract meaningful insights, and tp show how Dask enables scalablity and efficient data processing when working with large datasets that may not fit entirely into memory easily.

The Delhi Metro dataset consists of multiple CSV files representing different operational aspects of the metro system. These datasets are relatively large, making them ideal for demonstrating the advantages of Dask over basic data processing libraries like Pandas.

The main objectives of this task are:
1. To load and process the large datasets of Delhi Metro efficiently.
2. To explore and understand the structure of the data.
3. To extract some important insights from the data.
4. To visualize findings using charts.
5. To prove the scalability and efficiency of python library - Dask.

*Tools and Technologies used in the FIRST TASK*
Python and some of its major helpful libraries like - 
1. Dask DataFrame - For data processing and scalability 
2. Pandas - For comparison and small data handling, and
3. Matplotlib – For data visualization

*Datasets used in the FIRST TASK*
The analysis is performed on the following four Delhi Metro datasets:
1. stop_times – Arrival and departure timings for metro stops
2. stops – Information about metro stations
3. trips – Trip-level data linked to routes
4. routes – Information about metro lines

*Breakdown of TASK 1*
1. Setup & Load Data
The first step involves loading all four datasets using Dask.
Since the datasets are large, only the top 30 records are displayed during result to avoid unnecessary memory usage.

2️. Data Exploration
Basic statistical analysis is performed on the stop_times table. It includes:
Finding the shape and size of the dataset
Listing the column names
Checking the data types

This helps in understanding the structure of the dataset before performing deeper analysis.

3️. Insight-1: Busiest Metro Stations
This analysis identifies the busiest metro station by counting how many times each station appears in the stop_times dataset. The station with the highest count is identified as the busiest station. 
Additionally, a bar chart is created to visualize the top 10 busiest metro stations.

4️. Insight-2: Peak Hours Analysis
In this insight, the peak travel hours of the Delhi Metro are identified. The hour is extracted from the arrival_time column and the number of stops per hour is calculated. The hour with the highest traffic is identified as the peak hour. Additionally, a bar chart is created to visualize metro traffic distribution across different hours of the day.

5️. Insight-3: Most Crowded Metro Lines
This insight focuses on identifying the most crowded metro line by counting the number of trips associated with each route. The route with the highest number of trips is identified as the most crowded line. 
A visualization of the top 10 most crowded metro lines is also created using a bar chart.

6️. Insight-4: Scalability Proof Using Dask
The final and most important part of the first task demonstrates the scalability using Dask. This is completed by:
Checking the number of partitions for each dataset,
Demonstrating lazy execution, where computations are not executed immediately,
Triggering actual execution using .compute(),
Processing all datasets efficiently without loading everything into memory.

A partition comparison chart is also created to visually prove how Dask divides large datasets for parallel processing.

*Outputs*
<img width="1022" height="668" alt="Image" src="https://github.com/user-attachments/assets/4797cfd9-974b-4f41-baf1-c9295ab6d87b" />

<img width="1238" height="712" alt="Image" src="https://github.com/user-attachments/assets/cb070ec9-9760-4209-b486-14872dd372c2" />

<img width="1250" height="707" alt="Image" src="https://github.com/user-attachments/assets/a875dd01-5d90-4ed4-b8d0-85cf208a120d" />

<img width="481" height="346" alt="Image" src="https://github.com/user-attachments/assets/75b5fabf-b129-4949-bdf3-ba5121df4290" />
