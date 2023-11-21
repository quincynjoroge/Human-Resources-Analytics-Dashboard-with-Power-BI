# Human Resources Analytics Dashboard with Power-BI
To create this dashboard we followed the following Key steps:
- **Building the data model and analyzing data**: In this step, we focused on 5 key areas:
  1. Requirements gathering
  2. Connecting to the data sources
  3. Data transformation
  4. Building the data model
  5. Writing the initial DAX measures
     
- **Report design**: In this step, we focused on 3 key areas:
  1. Branding
  2. Defining the report layout
  3. Building the report with chart visualizations

**Objective of this Project:**

To build a report using datasets from a Tech company called QWIT Ltd. QWIT Ltd HR team wants to be able to monitor key metrics on employees. Their secondary goal is to understand what factors impact employee attrition.

**The Dataset**

In this case study, I utilized the Kimball Model approach to construct a snowflake schema, employing facts and dimensions extracted from the provided dataset. The fact table, the core of the schema, houses Performance Ratings, encompassing details on employee yearly reviews, facilitating QWIT Ltd performance management efforts. This table comprises 11 distinct columns and accommodates multiple rows per employee.

To enhance data context, I incorporated five dimension tables: Employee, EducationLevel, RatingLevel, SatisfiedLevel, and Date. These tables enable us to delve deeper into the 'who, what, when, where, and why' of employee performance.
