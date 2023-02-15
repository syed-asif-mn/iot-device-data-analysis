# iot-devices-data-analysis

IOT devices data is derived from a JSON file and analyzed using SparkSQL. 
<ol>
<li>Read the data into a Dataframe.</li>
<li>Convert the Dataframe into a temporary view called iot.</li>
<li>Count how many devices are there from each country and display the output.</li>
<li>Display all the countries whose carbon dioxide level is more than 1400. Sort the output in descending order.</li>
<li>Select all countries' devices with high-levels of C02 and group by cca3 and order by device_ids.</li>
<li>Find out all devices in countries whose batteries need replacements.</li>
</ol>

[View Notebook on Kaggle](https://www.kaggle.com/syedasifmn/iot-devices-data-analysis/)
