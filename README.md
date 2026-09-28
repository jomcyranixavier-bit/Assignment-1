# Assignment-1
Steps and Syntax															
															
1) Sum, Count, Average:
         				
SUM(range)  SUM(D2:D35	

COUNT(range) COUNTA(B2:B35)		

AVERAGE(range) AVERAGE(D2:D35)															
															
3) Min and Max
           				
MIN(D2:D35)		

Max(range) MAX(D2:D35)															
															
• Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.			

IF(D2:D35>=500,"High price","Standard price")															
															
• Calculate the total price for products in the 'Electronics' category using the SUMIF function.	

SUMIF(F10:F35,"Electronics",D2:D35)															
															
• Determine the count of products with a price less than $100 using the COUNTIF function.		

COUNTIF(D2:D35, "<100")															
															
5) Text Formatting - LEFT, RIGHT, MID:
 					
• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function.			LEFT(A2:A35,2)		

• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.	RIGHT(A2:A35,2)	

• Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function. MID(A2:A35,"4","3")		
