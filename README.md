# Historical-Weather-Forecast-Comparison-to-Actuals
It is a practice project of IBM's course on Coursera (Hands-on Introduction to Linux Commands and Shell Scripting).

1.Background: You've been tasked by your team to create an automated Extract, Transform, Load (ETL) process to extract daily weather forecast and observed weather data and load it into a live report to be used for further analysis by the analytics team. As part of a larger prediction modelling project, the team wants to use the report to monitor and measure the historical accuracy of temperature forecasts by source and station. As a proof-of-concept (POC), you are only required to do this for a single station and one source to begin with. For each day at noon (local time), you will gather both the actual temperature and the temperature forecasted for noon on the following day for Casablanca, Morocco.

2.Solution: 
  a.Initialize a weather report log file
  b.Write a Bash script that downloads the raw weather data, and extracts and loads the required data
  c.Schedule a Bash script rx_poc.sh to run every day at noon local time
  d.Apply advanced Bash scripting to produce reporting metrics
  e.Create a script to report historical forecasting accuracy
  f.Create a script to report the minimum and maximum absolute errors for the week

3.Learning Skills
  a.Download raw weather data
  b.Extract data of interest from the raw data
  c.Transform the data as required
  d.Load the data into a log file using a tabular format
  e.Schedule the entire process to run automatically at a set time daily

4. Others: For this practice project, we'll use the weather data package provided by the open source project wttr.in, a web service that provides weather forecast information in a simple and text-based format.
