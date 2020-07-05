# Soap UI Data driven

### This project is created only for learning purpose and I have used the api of "http://petstore.swagger.io"

### Download and add the jxl.jar in your soap ui > bin folder

### Download the PET-soapui-project.xml and DataDriven.xls file

### Edit the excel file as per your need 
  1. Do not make any changes in the TC column.
  2. Do not specify any value in the cell which are kept blank.
  3. Add the data as per the pet payload example given in api of "http://petstore.swagger.io"

### How to run this project
  1. Open Soap UI and Click on File > Import Project and select downloaded PET-soapui-project.xml file
  2. Open the testuite "**pet**" > open testcase "**Run TC**" > open "**Script**" file
  3. Change the excel file path i.e., at line number #8 with the download excel file
  4. Change the Project path at line number #59
  5. Save the project
  6. Run the TestCase "**Run TC**"
