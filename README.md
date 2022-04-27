# Analysis for GDP in India
# Aim
To check if there is any relationship between per capita GDP with dropout rates in education.

# Problem Description
[NITI Aayog](https://en.wikipedia.org/wiki/NITI_Aayog) (National Institution for Transforming India) is a policy think tank of the Government of India; it provides strategic inputs to the central and the state governments to achieve various development goals. In the past, NITI Aayog has played an important role in initiatives such as Digital India, Atal Innovation Mission and various agricultural reforms and have designed various policies in education, skill development, water management, healthcare, etc.
In this project NITI Aayog will provide top-level recommendations to the Chief Ministers (CMs) of various states, which will help them prioritise areas of development for their respective states. Since different states are in different phases of development, the recommendations should be specific to the states.
The overall goal of this project is to help the CMs focus on areas that will foster economic development for their respective states. Since the most common measure of economic development is the GDP, you will analyse the GDP of the various states of India and suggest ways to improve it.

[Gross domestic product (GDP)](https://en.wikipedia.org/wiki/Gross_domestic_product) at current prices is the GDP at the market value of goods and services produced in a country during a year. In other words, GDP measures the 'monetary value of final goods and services produced by a country/state in a given period of time'.GDP can be broadly divided into goods and services produced by three sectors: the primary sector (agriculture), the secondary sector (industry), and the tertiary sector (services). It is also known as nominal GDP. More technically, (real) GDP takes into account the price change that may have occurred due to inflation. This means that the real GDP is nominal GDP adjusted for inflation. 

Total GDP divided by the population gives the **per capita GDP**, which roughly measures the average value of goods and services produced per person. The **per capita income** is closely related to the per capita GDP (though they are not the same). In general, the per capita income increases when the per capita GDP increases, and vice-versa. For instance, in the financial year 2015-16, the per capita income of India was ₹93,293, whereas the per capita GDP of India was $1717, which roughly amounts to ₹1,11,605. 

# Data
The data is sourced from https://data.gov.in/, an Open Government Data (OGD) platform of India. The download instructions are provided in the next segment. The data for GDP analysis of the Indian states is divided into two parts:
- Data I-A: This dataset consists of the GSDP (Gross State Domestic Product) data for the states and union territories.
- Data I-B: This dataset contains the distribution of GSDP among three sectors: the primary sector (agriculture), the secondary sector (industry) and the tertiary sector (services) along with taxes and subsidies. There is separate dataset for each of the states. We will read the dataset for the available states and join these (in Python) if needed.
