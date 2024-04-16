# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [X] Add datasets used to the `datasets/` folder: SuperStoreUS-2015_dataset.xlsm

#### Files

- [X] **Initial**: Add file to the `exercises/`  folder with the name: SuperStoreUS-2015_dataset_vm_exercise_1.xlsm
- [X] **Solution**: Add file to the `exercises/`  folder with the name: SuperStoreUS-2015_dataset_vm_exercise_1.xlsm, which contains macro titled MacroVMExercise1

#### Learning Objective

Create and calculate new "Order Date" related fields in the SuperStore dataset, which will aid Data Analysts in data mining orders by different "Order Date" slices.

#### Context

SuperStore recognizes that customer service, customer retention, and customer repeat are critical to its success. One aspect of excellent customer service is in the timely processing and shipment of orders.  SuperStore would like to analyze this order-to-ship days and see if there is any connection between the number of days and the time of year the order is received.  If there is a correlation, SuperStore can take the necessary steps to adjust any flawed underlying operational processes.

#### Steps to be executed by the student (max 6)

- Create, populate, and bold new order_month column: Month of "Order Date" column
- Create, populate, and bold new order_quarter column: Quarter of "Order Date" column
- Create, populate, and bold new order_to_ship_days column: Number of days between "Order Date" and "Ship Date"

#### Exercise question:
How will a Data Analyst determine inefficiencies between the time an order is received and the order is shipped?  Is there any correlation between the number of days between "Order Date" and "Ship Date" and the year, month or quarter the order is received?

#### End goal:

<img width="1229" alt="ScreenshotMacroVMExercise1" src="https://github.com/jayneygulley/sme-bi-course-application/assets/166956603/fe9860b0-55ff-4f52-ad43-ffd25353da22">


## 2nd VM Exercise

#### Dataset

- [X] Add datasets used to the `datasets/` folder: SuperStoreUS-2015_dataset.xlsm

#### Files

- [X] **Initial**: Add file to the `exercises/`  folder with the name: SuperStoreUS-2015_dataset_vm_exercise_2.xlsm
- [X] **Solution**: Add file to the `exercises/`  folder with the name: SuperStoreUS-2015_dataset_vm_exercise_2.xlsm, which contains macro titled MacroVMExercise2

#### Learning Objective

Create and calculate new "Sales" and "Profit" related fields in the SuperStore dataset, which will aid Data Analysts in gaining key insights into the financial performance and efficiency of the business.

#### Context

SuperStore understands that accurate and comprehensive financial metrics need to be available to management.  Sales and Profit data is extremely important; however, financial ratios and percentages help management view the business' financial numbers in more insightful context.    

#### Steps to be executed by the student (max 6)

- Create, populate, bold, and percentage format new profit_to_sales column: What percent of a sale is profit
- Create, populate, bold, and percentage format new shipping_to_sales column: Shipping cost to sales ratio
- Create, populate, bold, and percentage format new discount_to_unit_price column: Discount rate

#### Exercise question:
How will a Data Analyst determine metrics to assess a firm's financial health?

#### End goal:

<img width="1394" alt="ScreenshotMacroVMExercise2" src="https://github.com/jayneygulley/sme-bi-course-application/assets/166956603/ff923a0d-9fd8-4ad3-b6ce-cf7cd0c27cc2">




