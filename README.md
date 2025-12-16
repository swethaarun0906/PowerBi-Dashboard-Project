# PowerBi-Dashboard-Project
This Power BI dashboard provides visual insights into hospital records, focusing on patient demographics, medical conditions, treatment costs, bed usage, and readmission rates. It enables hospital staff and administrators to monitor key performance indicators (KPIs) and improve healthcare service delivery

 
# Key Metrics & Visuals
         
Count of Patient_ID by Gender	Bar Chart	Displays gender distribution of patients
Count of Patient_ID by Age	Tree Map	Shows age group segmentation of patients
Sum of Cost by Condition	Donut Chart	Compares treatment costs for different conditions
Sum of Cost by Length_of_Stay	Line Chart	Correlates treatment cost with length of stay
Bed Occupancy	Gauge	Indicates total bed occupancy rate
Average Treatment Cost	Gauge	Displays the average cost per patient
Readmission Rate	Gauge	Reflects patient readmission percentage

# Filters/Slicers Used
•	Procedure / Condition (multi-select hierarchy)
•	Condition (e.g., Cancer, Heart Attack, Diabetes, Stroke)
These filters allow users to drill down by treatment type or medical condition to analyze specific patient groups.

# KPIs Calculated
KPI	Description	             Approx. Value
Bed Occupancy	 Number of beds occupied / total beds	                    12.35
Average Treatment Cost	 Mean cost per patient across all treatments	                    8.37K
Readmission Rate	 % of patients readmitted after discharge	                     0.27

# Assumptions
•	Cost values are aggregated based on patient condition and duration of stay.
•	Readmission is defined as a patient returning within 30 days of discharge.
•	Bed occupancy is calculated as the average across the selected date range.

# Design Choices
    Data: <a href "https://github.com/swethaarun0906/PowerBi-Dashboard-Project/blob/main/hospital%20data%20analysis.csv"</a> 
    Dashboard: https://github.com/swethaarun0906/PowerBi-Dashboard-Project/blob/main/Hospital%20record%20project.pbix 
•	Dark Theme: Enhances readability for hospital control room displays.
•	Tree Maps and Donuts: Provide intuitive overviews of demographic and financial distributions.
•	Gauges: Quick-glance KPIs for decision-makers on live dashboards.
		

