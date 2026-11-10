# Global-Water-Supply-and-Access-Analysis-2020-
An exploratory analysis of the Global 2020 water supply dataset, examining access to drinking water across countries. The project compares urban and rural populations across four service levels: basic, limited, unimproved, and surface water, using visualisations to identify access patterns, disparities, and populations with limited water services.
Situation;
This analysis was one of my final projects. The brief was to apply what I had learned to a real-world dataset. I chose global water access because it is a key development measure that varies widely between countries and between urban and rural areas. I wanted to understand how access to water services differed across the world in 2020 and how large the urban-rural gap was.

Task;
Using a 2020 national dataset on water-service use, I set out to answer:

How much of each country’s population has basic water access, and how widely does this vary?
How do urban and rural areas compare?
How many people still depend on limited, unimproved or surface-water sources?
How does each country’s urban versus rural population share relate to its population size?

Data: one row per country, with its income group, total and urban population, and the percentage of people at each water-service level (basic, limited, unimproved, surface water), split into national, rural and urban figures.
Action
Reviewed the raw dataset in Google Sheets and checked for gaps. Some cells, especially for small territories, contain “NAN”.
Calculated world totals, including total population (7,786,695,108), total urban population (4,375,308,463) and the urban share (56.19%).
Built a statistics table of MAX, MIN, MEAN, MEDIAN, MODE, Q1, Q3, IQR and SD for each water-service measure.
Created four visualisations:
a line chart of urban versus rural population share against national population size
a box plot of the water-service measures
a stacked chart of national access by service level
a stacked chart of urban access by service level

Result;
Access is high overall, with a long tail of low-access countries. The national average for basic water access is about 89.9%, the median is 97.3% and the minimum is 37%. Most countries are near full coverage, while a small group is much lower.
The urban-rural gap is clear. Average basic access is about 94.7% in urban areas and 81.3% in rural areas. The lowest rural value is about 22%, against about 50% for urban.
Rural areas rely more on unimproved sources. The average share is about 8.7% rural versus 1.7% urban.
Surface-water use is a rural problem. The highest rural share is about 40.5%, against about 6.4% in urban areas.
Urban population share changes with country size, as the line chart shows.

Averages are across the countries in the dataset.
