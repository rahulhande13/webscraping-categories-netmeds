# Scraping Selected Categories on netmeds.com using Python and Beautiful Soup.

netmeds.com is a one-stop healthcare shop containing list of product with different categories. There are exclusive discounts all year round. They also call themselves as India Ki Pharmacy where consumer can buy medicines and wellness products using online portal or app.

The page https://www.netmeds.com/non-prescriptions/diabetes-support provides a list of categories on netmeds.com. In this project, we will select category and retrieve information from this page using web scraping : the process of extracting information from a website in an automated fashion using code.

We'll use the Python library requests and beautifulsoup4 to scrape data from this page.

## Project Outline:
Here's an outline of the steps we'll follow:

1. Define the webpage.
2. Download the webpage using requests.
3. Parse the HTML source code using BeautifulSoup.
4. Extract the list of category Names.
5. Extract the list of Sub-category(name and href).
6. Extract all Category and their Sub-category data.
7. Extract Product Name, BuyPrice, MRP and Discount from Sub-category.
8. Extract Current Page and Next Page Product Details (Product Name, BuyPrice, MRP and Discount) from Sub-category. Get the details till the page has next button.
9. Scrape the data by compiling Python lists and dictionaries.
10. Save it into a CSV file and read the CSV file.
11. By the end of the project,

We will create a CSV file named as Category name containing list of product details of every sub-category in the following format.
Category Name,Sub Category Name,Product Name,Buy Price,MRP,product_discount

Diabetes Support,Diabetes Care - Ayurveda,Kapiva Karela Jamun Juice 1 ltr, 296.65, 349.00,15%



Check out Jupyter Notebook here : https://jovian.com/rahulhande2780/finalscrape-netmeds-com-project
