# Project Discription:
The objective of this case study is to Detect fraudulant and non fradulant calimants. 
## Column Descriptions
### Feature Important for Model Possible Values: 
##### Region 1 - 8 regions - NE,NW,SE,SW,E,W,N,S 
##### State 1 -Names fo state Area 1 -Urban,Rural 
##### City 1 -Hyderabad,Delhi,Goa 
##### Consumer profile/ type 1 -Business customer /Personal 
##### Product category 1 -Entertainment / Household Product type 1 -TV / AC Part number / Issue category 1 0- -No issue / 
##### No componenent, 1- repair, 2-replacement 
##### Claim value 1 -would we have this value during claim process, probably an approximate claim value could be tagged Service centre 1 
##### -Service Centre code (10,11,12,13,14,15) 
##### Age in days 1 -Age of the product 
##### Purchased from 1 -Dealer,Manufacturer,Internet 
##### Call details 1 -Call duration in minutes 
##### Purpose 1 -Claim,Complaint,Other 
##### Fraud (1 if Fraud else 0) 1 1 or 0 : - Fraud-1 Non-Fraud-0
# Project overview:
### Step-1: EDA:
1:Import dataset using pandas. 
2:check for null values, data types of columns. 
3:Performed some visualization so as to analyze the data. 
4:Comeup with the conclusion that the data set is highly imbalanced. 
5:Find outliers using boxplots.
### Step-2: Feature Engineering:
1:Use some encoding techiniques.
2:Handle outliers.
3:make dataset balanced.
4:Scale the data.
### Step-3: Feature Selection:
1: Select features by using various methods.
2: split data in train and test.
### Step-4: Model Building:
Build various model like Logistic Regression, KNN, SVM, Decision Tree, Ranfdom Forest.
### step-5:Model Deployment:
Deploy model having good accuracy over train and test data using streamlit.
