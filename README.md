# Logistics-_Weekly_Survey_ETL
Developed an ETL process to transform and standardize logistics data from Excel sources, accurately mapping product models and aggregating quantities based on promotional bulletin criteria for integration into survey reporting.

Currently the shipping reports are working.

Step 1. Organize folder structure to match path. Should be just to edit: r'C:/Users/NAME/'
Step 2. Test to see if there are any errors if not proceed to Step3

Steps to download csv files in order:
Step 1. Structure: go to Fishbowl reports > Sales Order Summary. 
Make sure you filter only these:
-Ship To State/province: All
-Apply Date Filter: Scheduled Fulfillment Date
-Date range        From 01/01/2025 to Any Future date
-Group By: Location Group

click:
-Show Historical Product Number
-Show SO Details
-Format Report For Exporting

Column:
-Customer
-Remaining
-Date Issued
-Ordered
-Sales Person
-Shipped

STEP 2.
SO Status only filter "In Progress", click ok and save csv file as the shipping.csv and shipping_entered.csv path should be:
(r'C:/Users/NAME/Documents/Reports/Gitfolder/Logistics-_Weekly_Survey_ETL/Surveys/testing/input_yes/shipping.csv')
(r'C:/Users/NAME/Documents/Reports/Gitfolder/Logistics-_Weekly_Survey_ETL/Surveys/testing/input_yes/shipping_entered.csv')

STEP 3.
SO Status only filter in "Issued", click ok and save csv file as the shipping.csv and shipping_entered.csv path should be:
(r'C:/Users/NAME/Documents/Reports/Gitfolder/Logistics-_Weekly_Survey_ETL/Surveys/testing/input_yes/shipping_partial.csv')
