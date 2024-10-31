# Mc D's Menu Nutritional Analysis
#
### **Introduction**
#
**Purpose**
- Help customers understand the nutrional values so that they can make informed decisions.
- To help the business for finding loop holes to fix and opportunities that they can take benefit of.
#
**Dataset**
- Dataset comprises of 20+ columns each of which represents a unique nutritional component.
- This dataset considers more than 200 items from different categories.
#
### **Methodology**
#
**Tools Used**
- Python (pandas, matplotlib)
#
**Analytical Technique Used**
- Descriptive Analytics
- Diaganostic Analytics
#
**Workflow**
- Before understanding the workflow of dataset I want to firstly explain some data points of this dataset which could be confusing in start. <br>
For most of the nutrients that are mentioned in this dataset. There's a follow up column which goes like `nutrientName % Daily Value`. <br>
This means the contribution of nutrient from this meal towards your daily intake. <br>
For example if for any nutreint X the X value is 12 and `X % Daily Value` is 50. It means that this food item is giving 50% of X nutrient in a single meal. <br>
Meaning this food item is rich in X. <br>
**NOTE:** Ideally a single meal should not contribute more than 25% to 30%, because it complicates the digestion for other nutrients. Because we are supposed to complete our nutrient intake throughout a whole day.
- Performed EDA in Python, using pandas, matplotlib, seaborn.
- Generated visualizations, to simplify the complex looking table structures to generate insights.
- Performed aggregate operations over several available categories, create visualizations for the same.
#
**Challenges**
- Only challenge was to understand, the concept of %Daily Value. <br>
Took help of internet and Generative AI to understand it, making my further analysis easier.
- Other challenge was to finding opportunities for business, that can help them, as this dataset majorly helps to educate the customers about the adverse effect of these food items, if consumed more.
