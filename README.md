
Data Manipulation and Reporting with Power BI

DESCRIPTION

Zomato is a restaurant aggregation and meal delivery service based in India. It is currently operating in several countries across the world. Zomato provides thorough information about numerous eateries as well as consumer reviews. Zomato's owners aim to find hidden irregularities in their company's data. The ultimate goal of this project is to examine the data in such a way that they can accurately assess their business performance.

The data (sample) is currently accessible in the form of a few Excel files, each of which contains information about multiple restaurants operating in a certain continent. The clients want to construct a consolidated and interactive Power BI report that will allow them to do the following:

  1. Derive data on the total number of restaurants worldwide, including continents, countries, and cities

  2. View data on a global scale with the capacity to drill down to a granular level

  3. Derive data on the restaurants with the highest average customer ratings

  4. Discover the restaurants with the lowest average costs

  5. Filter and view information on the restaurants based on:

  I) Their geographical dimensions such as continent, country, and city.
  
  II) The service they provide, such as online ordering or reservation services.
  
  III) The average rating slab by the color.

   6. Identify the restaurants with the most cuisines served

   7. Design a multi-page report that suits Zomato's theme with easy navigation across  

   sections.

   8. Allow Zomato users to be able to access this information from both a web browser 
           and a mobile device.
           Aim of the project:

   The aim is to construct a consolidated and interactive PowerBI report that will allow Zomato to quickly assess the required data.


   Steps that will help in the completion of the project:

   1. Import the data from all available Excel files

   2. Data transformation: 

   Make sure the City column names are corrected 

   For example: 

   “Sí£o Paulo” should be corrected to “São Paulo”
    Ensure the city name isn't ambiguous

  For example: 

  “Cedar Rapids/Iowa City” should be corrected to “Cedar Rapids”

  “ÛÁstanbul” should be corrected to “Istanbul”
 
  3. Remove any columns that aren't being used 

  4. Create two columns to display the Restaurant Name and Restaurant Address

  5. Make a separate table for the list of the cuisines that each restaurant serves

  6. As it's a dimension table, the Country-Code table must only include unique and non-blank values


  Steps to use DAX in the project
 
  1) Add a Rating color column in an appropriate table with the data rows in the format given belo                                               

  Aggregate rating                        
  Rating color
   Above 4.5  
  Dark Green
  4 to 4.4  
  Green

  2) Create the following measures in the appropriate tables 
 
  a. Restaurant count
 
  b. Average cost

  c. Average rating 

  d. Cuisine count

  3) Create a new column in the Country Code table and name it “Continent” and create the values using the below-mentioned convention

  Note: The mapping is continent - country, for example ''Africa – South Africa'' 


  Files Required for the Project

All the files required to complete this project can be found in the link given below:

https://github.com/Simplilearn-Edu/Power-BI-Datasets.git
