# Overview
![Image](https://github.com/user-attachments/assets/69080224-65cd-4230-bc7e-4fbd8dae30e1)

This project investigates the relationship between education indicators (such as literacy rate and physician density) and economic performance (measured by GDP per capita, GDP growth, and unemployment rate) across countries and continents.

Together, these datasets provide insight into how human capital formation — primarily through education and health infrastructure — influences economic outcomes globally.

# Research Questions

This project explores five key questions:

How does literacy rate influence GDP per capita across different continents?

Is there a statistically significant relationship between physician density and GDP per capita?

Do countries with higher literacy rates experience faster GDP growth?

What threshold of literacy rate is associated with a transition from low to middle-income status (GDP per capita)?

Which countries have higher unemployment rates, and how does this affect their literacy rate and GDP per capita?

Data Description
Variable	Description
country	Country name
continent	Continent to which the country belongs
literacy_rate	Percentage of literate adults
physician_density	Number of physicians per 1,000 people
gdp_per_capita_(current_usd)	GDP per capita in current USD
gdp_growth_(%_annual)	Annual GDP growth rate
unemployment_rate_(%)	Percentage of unemployed labor force
gdp_per_capita_category	Income classification (Low, Mid, High)
Methodology

The analysis was conducted in Python using pandas, scipy, matplotlib, and sklearn.
It includes:

# Descriptive Statistics — Summary of central tendencies and variability of all key variables.

# Correlation Analysis — Pearson correlation between education and economic indicators.

# Regression Models

Linear Regression for GDP per capita vs. physician density.

Logistic Regression for identifying literacy rate thresholds that separate low and mid-income countries.

Visual Analysis — Scatterplots for key relationships (e.g., literacy vs GDP).

Comparative Analysis — Ranking of countries by unemployment and its link to literacy and GDP.

Key Findings
# Literacy and GDP per Capita

A strong positive correlation exists between literacy rate and GDP per capita globally.

Continents with higher literacy levels (Europe, North America) show higher GDP per capita.

Literacy improves productivity, innovation capacity, and labor efficiency.

 # Physician Density and GDP per Capita

A significant positive relationship suggests that countries investing in healthcare (more physicians per population) also enjoy stronger economies.

Indicates that education and health are complementary drivers of growth.

# Literacy and GDP Growth

Countries with higher literacy rates tend to maintain more stable and higher GDP growth.

Human capital enhances adaptability to technological change and economic resilience.

# Literacy Threshold for Middle-Income Transition

Logistic regression estimates a threshold literacy rate (≈ 70–80%) associated with the shift from low to middle-income status.

Below this, economic growth is typically slower and volatile.

# Unemployment, Literacy, and GDP

Countries with high unemployment generally have lower literacy and GDP per capita.

Educated labor markets show lower unemployment and more diversified economies.

Policy Implications

Investing in education yields long-term economic returns through skilled labor and innovation.

Balanced investment in education and healthcare enhances labor productivity and human capital.

Governments should target literacy improvements in the 60–80% range to push countries toward middle-income status.

Tackling unemployment requires aligning education systems with market demand.

Visual Outputs

The analysis provides the following key visualizations:

📈 Scatterplots: Literacy Rate vs GDP per Capita (by continent)

🧮 Linear Regression: Physician Density vs GDP per Capita

🔍 Correlation Matrices

📊 Top 15 Countries by Unemployment Rate

Tools & Libraries
Tool	Purpose
pandas	Data manipulation & cleaning
numpy	Numerical computation
matplotlib	Visualization
scipy	Statistical testing
sklearn	Logistic regression modeling
# Conclusion

Education acts as a cornerstone of economic development.
Countries with higher literacy rates tend to have stronger economies, more robust healthcare systems, and lower unemployment.
The findings underscore that education is not just a social investment — it is an economic imperative.

