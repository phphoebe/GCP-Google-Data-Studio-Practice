# Google Data Studio Practice Projects

### **PDF Version Report:**
* [Sales Report](https://github.com/phphoebe/googledatastudio-practice/tree/master/1.Sales%20Report)
* [Digital Perforamnce Report](https://github.com/phphoebe/googledatastudio-practice/tree/master/2.Digital%20Performance%20Report)

### **Interactive Data Studio Report Link** 
:octocat: *Please right click "open link in new tab/window":*
* **[Sales Report](https://datastudio.google.com/reporting/57651fce-ff4e-42cd-879b-866ce879f7d2)**
* **[Digital Performance Report](https://datastudio.google.com/reporting/edbf153e-24bf-4a8a-a77f-36a3a363b91e)**

:octocat: Both reports contain **multiple pages**. Click the left/right arrow at the top-left corner to switch between pages:
![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Multiple%20Pages.PNG)


 ## :sparkles: Key Takeaways :sparkles: 

### **1. KPI Scorecards for key Summary Statistics and Comparisons**
* Search and Choose metrics available directly from data source. 
* **Custom Date Range** (*Last week starts Monday* for this report). Data Studio offers **Auto** and a variety of **Custom** date range options such as last 28 days, this month to date etc.
* **Comparison Date Range** – add in a comparison to show how key metrics have changed since previous period.
* **Style Options**: customize font, color, decimal precision, display as compact number etc.). Copy and Paste existing scorecards and change metrics to maintain consistent styling. 

![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/KPI%20Scorecard.PNG)


### **2. Time Series Charts for Analyzing Trends**
* Show Transactions (metric) by Week of Year (dimension) with Year on Year (YoY) Comparison (comparison date range: Previous Year).

![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/WOW%2C%20YOY%20Comparison.PNG)


* Show Revenue (metric) by Week of Year (dimension) since the beginning of the year (custom date range: Jan 1 2020 – Dec 31 2020) with Year on Year (YoY) Comparison (comparison date range: Previous Year).
* Style Set: show Cumulative series with Data Points on charts. 
Switch to View Mode, it shows that Google Merchandise Store has so far made nearly $22B in revenue. 

![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Cummulative%20Revenue.png)


### **3. Tables for Presenting Detail (with Date Comparion):**
* Metrics for last 7 days with **% change comparison of previous period**.

![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Dynamic%20Data%20Comparison.PNG)

### **4. Applying Interaction Filter (Geo and Treemap)**
* Show data for one area only, or multiple (*Montreal and Toronto* for example in this screenshot) based on user selection to enhance user interaction. 
![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Interactive%20Filter.PNG)

### **5. Filtering by Dimensions**
* Add Dynamic Data Filter to show and filter data by dimensions (e.g. *Campaign* or *Country*) based on reporting needs.
* Search Box available for direct type in to search for specific values. 
![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Filters%20by%20Dimension.PNG)

### **6. Calculated Metrics with Formulas (Custom Metrics)**
* CTR = Clicks/Impressions (Data Type: percent; Aggregation Level: AVG)
* CPA = Media Spend/Total Conversions (Data Type: Currency) 
![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Calculated%20Fields%20(custom%20metrics).png)

### **7. Custom Dimensions with CASE + IN**
* Utilize **SQL CASE Statement and IN Operator** to create a custom dimension (Language) in order to demonstrate campaign metrics for different language versions. 
![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Custom%20Dimensions%20(CASE%2BIN).PNG)

### **8. Custom Dimensions with CASE + REGEXP_MATCH**
* Utilize **SQL CASE Statement** and **Regular Expressions (Regex)** to create a new custom dimension (Type) to label the language version for each campaign. 
![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Custom%20Dimensions%20(CASE%20%2B%20REGEXP_MATCH).PNG)

### **9. Conditional Formatting for Report Customization and easier Navigation**
![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Conditional%20Formatting.PNG)
![](https://github.com/phphoebe/googledatastudio-practice/blob/master/Images/Conditional%20Formatting%202.PNG)


### Acknowledgement 
The Sales Report project is part of the [Build Insightful Dashboards with Google Data Studio](https://www.udemy.com/course/build-interactive-dashboards-and-reports-with-google-data-studio/) course taught by Annabel Lyle (Data Analyst - Data Studio & Google Analytics). The data used is Sample Google Analytics data.

The Digital Performance Report project is part of the [Dynamic Dashboards and Data Analysis with Google Data Studio](https://www.udemy.com/course/dynamic-dashboards-and-data-analysis-with-google-data-studio/) course taught by Lachezar Arabadzhiev (Performance Analytics and Visualization Professional). The data used is Google Analytics data from Google Merchandise Store, and Google Sheets datasets owned by the instructor and are not publicly available here.

