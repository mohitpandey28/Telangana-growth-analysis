# Telangana-growth-analysis

## Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNWY1NTI3OTMtODc1OS00YjE3LTgwNGQtNDZhZDQ3MDBjOWE4IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9


### About Telangana

Telangana is India's youngest state, formed in 2014. capital city is Hyderabad, is a global IT hub with famous landmarks like the Charminar.
The state has seen fast economic growth, especially in IT, pharmaceuticals, and manufacturing.
Telugu and Urdu are the official languages.
Government is focused on digital services, development projects, education. More information about Teleangana

#### Objectives:
Explore Stamp Registration, Transportation and Ts-Ipass Datasets.
Understand their attributes, categories and time period.
Analyze trends and patterns within each department.
Identify growth opportunities and areas needing attention.
Find correlation among these departments and report the overall growth of the state through insights and relevant visuals such as shape maps.

### Load the dataset
This dataset encompasses information from five CSV files, each providing valuable insights into different aspects of Telangana's economic landscape:

##### dim_districts:
dist_code: District code or identifier.
district: District name.
##### dim_date:
month: Starting date of each month.
Mmm: Month name.
quarter: Associated quarter.
fiscal_year: Corresponding fiscal year.
##### fact_stamps:
dist_code: District code.
month: Starting date of each month.
documents_registered_cnt: Total count of registered documents.
documents_registered_rev: Total revenue from registered documents.
estamps_challans_cnt: Count of e-stamps challans.
estamps_challans_rev: Revenue from e-stamps challans.
##### fact_transport:
dist_code: District code.
month: Starting date of each month.
Vehicle sales by fuel type: Petrol, Diesel, Electric, Others.
Vehicle sales by class: Motorcycles, Motorcars, Auto rickshaws, Agriculture, Others.
Vehicle sales by seating capacity: 1-3, 4-6, Above 6.
Other categories: Brand new, Pre-owned, Non-Transport, Transport.
##### fact_TS_iPASS:
dist_code: District code.
month: Starting date of each month.
sector: Industry category (e.g., Automobiles, Beverages).
investment in cr: Investment in crores.
number_of_employees: Number of employees in the sector.
This comprehensive dataset provides a multi-dimensional view of economic activities, including district details, monthly timelines, document registrations, vehicle sales, and industrial investments in Telangana.


### 1. Documents Registered Count:
Rangareddy, Medchal_Malkajgiri:
Cause: High population density and economic activities leading to increased document registrations.
Implication: High document count signifies robust economic and real estate activities.
Prescription: Streamline documentation processes, enhance digital services, and ensure transparent property transactions.
### 2. Documents Registered Revenue:
Rangareddy, Medchal_Malkajgiri, Hyderabad, Sangareddy:
Cause: Economic and real estate activities leading to higher revenue from stamp duty.
Implication: Increased revenue reflects economic strength and real estate transactions.
Prescription: Ensure transparent and efficient revenue collection processes, explore digital payment options, and monitor property market dynamics.
### 3. eStamps Challans Count:
Rangareddy, Medchal_Malkajgiri:
Cause: Economic and industrial activities contributing to a higher volume of stamp duty transactions.
Implication: Increased challans indicate frequent property transactions and business activities.
Prescription: Implement efficient digital stamping processes, facilitate online transactions, and ensure ease of doing business.
### 4. eStamps Challans Revenue:
Rangareddy, Medchal_Malkajgiri, Hyderabad, Sangareddy:
Cause: Economic and real estate activities leading to higher revenue from stamp duty.
Implication: Increased revenue reflects economic strength and real estate transactions.
Prescription: Ensure transparent and efficient revenue collection processes, explore digital payment options, and monitor property market dynamics.
### 5. Fuel Types (Petrol, Diesel, Electric, Others):
Rangareddy, Medchal_Malkajgiri, Hyderabad, Sangareddy, Nizamabad, Khammam, Nalgonda, Yadadri Bhuvanagiri:
Cause: Varied fuel consumption patterns based on urbanization, economic activities, and industrialization.
Implication: Different fuel types reflect the region's energy infrastructure and environmental concerns.
Prescription: Promote electric and eco-friendly vehicles, invest in sustainable energy solutions, and monitor air quality.
### 6. Vehicle Classes (Motorcycle, MotorCar, AutoRickshaw, Agriculture, Others):
Rangareddy, Medchal_Malkajgiri, Hyderabad:
Cause: Diverse economic activities contributing to various types of vehicles.
Implication: Vehicle class distribution reflects economic diversity and transportation needs.
Prescription: Plan infrastructure for diverse vehicle types, promote sustainable transport, and manage traffic accordingly.
### 7. Seat Capacity (1 to 3, 4 to 6, Above 6):
Rangareddy, Medchal_Malkajgiri, Hyderabad, Sangareddy:
Cause: Varied vehicle seat capacities based on economic activities and urbanization.
Implication: Seat capacity distribution reflects transportation needs and preferences.
Prescription: Plan transportation infrastructure, encourage shared mobility, and consider urban planning for efficient traffic flow.
### 8. Brand New and Pre-Owned Vehicles:
Rangareddy, Medchal_Malkajgiri, Hyderabad, Sangareddy:
Cause: Economic prosperity and preferences influencing vehicle purchase choices.
Implication: Distribution of new and pre-owned vehicles reflects consumer behavior and market dynamics.
Prescription: Monitor consumer trends, support the automotive industry, and ensure transparent resale processes.
### 9. Category (Non-Transport, Transport):
Rangareddy, Medchal_Malkajgiri, Hyderabad:
Cause: Economic activities influencing the distribution of transport and non-transport vehicles.
Implication: Category distribution reflects the region's economic structure and mobility needs.
Prescription: Implement sustainable urban planning, invest in public transportation, and promote eco-friendly mobility solutions.
### 10. Investment in CR:
Rangareddy, Medchal_Malkajgiri, Sangareddy, Peddapalli:
Cause: High investments in specific sectors indicating economic focus and development plans.
Implication: Sector-wise investments reflect the region's economic priorities and growth prospects.
Prescription: Further investigation into local economic and development policies, collaboration with stakeholders, and continuous monitoring for dynamic policymaking.
### 11. Number of Employees:
Rangareddy, Medchal_Malkajgiri, Sangareddy, Yadadri Bhuvanagiri:
Cause: Varied employment numbers based on economic activities and industrial presence.
Implication: Employment distribution reflects the region's economic diversity and job opportunities.
Prescription: Collaborate with local authorities for targeted skill development, monitor employment trends, and adapt policies for workforce needs.
