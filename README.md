# 🌍 Global Health & Pharmaceutical Spending: Aging, Disease Burden, and Investment Insights

**DADS5001:** Presented by Sumonsiri (6720422007) and Parita (6720422012)

**Purpose:**  
This presentation analyzes global health and pharmaceutical spending across different income groups in the context of aging populations, disease burden (Disability-Adjusted Life Years: DALYs), and health outcomes (Life Expectancy). The goal is to identify trends and inform evidence-based policy insights.

---

## Data Sources:
1. World Bank Data: https://databank.worldbank.org/reports.aspx?source=2&country=WLD#
2. OECD Data: https://www.oecd.org/en/data/datasets.html?orderBy=mostRelevant&page=0&q=drug
3. Institute For Health Metrics and Evaluation: https://vizhub.healthdata.org/gbd-results/

---

## Table of Contents:
1. [Global Health Spending Landscape](#1-global-health-spending-landscape)
2. [Aging Society & Life Expentancy](#2-aging-society--life-expentancy)
3. [OECD Focus: Pharmaceutical Spending](#3-oecd-focus-pharmaceutical-spending)
4. [Global Disease Burden Trends (GBD)](#4-global-disease-burden-trends-gbd)
5. [Linking Disease Burden to Spending](#5-linking-disease-burden-to-spending)
6. [Conclusion & Policy Implications](#6-conclusion--policy-implications)

---

## 1. Global Health Spending Landscape

Health investment is a key driver of health outcomes worldwide. This section highlights global health expenditure patterns, temporal trends, and disparities across income groups.  

- **Global Health Expenditure % of GDP (Year 2022)**  

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure1.1.png?raw=true" width="900" />

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure1.1_Table.png?raw=true" width="400" />

*Figure 1.1: Regional differences in health expenditure, showing high spending in North America and Europe, and low spending in parts of Africa and South Asia.*

- **Health Expenditure per Capita & % of GDP by Income Group (Year 2010–2022)**  

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure1.2.png?raw=true" width="900" /> 

*Figure 1.2: Health expenditure trends over time, showing both per capita spending and spending relative to GDP. High-income countries consistently allocate more resources and a larger share of GDP to health than lower-income groups, while low-income countries lag behind.*

- **Distribution of Health Expenditure % of GDP Across Income Groups**  

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure1.3.png?raw=true" width="900" /> 

*Figure 1.3: Variability within income groups is evident; some upper-middle-income countries outperform peers, while low-income countries show limited investment in health services.*

- **Avg. Out-of-pocket Share of Health Expenditure, by Income Group (%) (Year 2022)**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure1.4.png?raw=true" width="900" />

*Figure 1.4: the average out-of-pocket share of health expenditure decreases as the income level of countries increases. Low-income countries have the highest average out-of-pocket share, while high-income countries have the lowest.*

- **Distribution of Out-of-pocket Share of Health Expenditure, by Income Group (%) (Year 2022)**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure1.5.png?raw=true" width="900" />

*Figure 1.5: The box plot illustrates the distribution of out-of-pocket health expenditure as a percentage of total health expenditure across different income groups in 2022. It reveals that lower-income groups not only have higher average out-of-pocket percentages but also show a wider spread and more outliers with very high percentages, indicating greater variability and potentially more extreme financial burdens on individuals in these countries compared to higher-income groups.*

- **Composition of Health Expenditure by Income Group (Year 2010-2022)**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure1.6.png?raw=true" width="900" />

*Figure 1.6: Lower-income groups' out-of-pocket expenditure consistently makes up a larger proportion of total health expenditure compared to higher-income groups. While there are some fluctuations, the general trend shows that out-of-pocket spending remained a significant component of health financing in lower-income countries from 2010 to 2022. In contrast, higher-income countries have a much smaller share of out-of-pocket expenditure relative to other forms of health financing.*

---
**Key Insights**  
1. Investment Gap: High-income countries consistently spend more, both per capita and as % of GDP.  
2. Financial Burden: Out-of-pocket expenses remain a major barrier in low- and lower-middle-income countries.  
3. Temporal Trends: Spending has increased across all income groups over 2010–2022, but disparities persist.

> "While global health expenditure has grown over the last decade, stark disparities remain. High-income countries consistently invest more in health systems, whereas low-income regions face persistent financial constraints, leaving populations vulnerable. Having explored these expenditure patterns and the financial burden on individuals, a natural question arises: how do these patterns relate to population structure? As countries move towards aging societies, they face increasing demands for healthcare services and greater per-capita spending. Examining the relationship between aging populations and health investment helps highlight potential challenges and opportunities for sustainable health policy.”

---

## 2. Aging Society & Life Expentancy

To understand the link between population aging and health investment, in this section we will first analyze the temporal trends of global longevity and population aging. We will specifically compare OECD countries, which feature a higher percentage of older adults (aged 65+), against non-OECD nations. Subsequently, we will investigate how these aging societies affect health expenditure per capita.

- **Trend of % Population ages 65+ and Life Expectancy at Birth (Year 2010-2022)**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure2.1.png?raw=true" width="900" />

*Figure 2.1: From 2010 to 2022, the plot reveals a clear upward trend in both the percentage of the population aged 65 and above and life expectancy at birth, suggesting a general increase in population aging and longevity across the countries included in the analysis.*

- **Trend of % Population ages 65+ and Life Expectancy at Birth: OECD vs Non-OECD (Year 2010-2022)**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure2.2.png?raw=true" width="900" />

*Figure 2.2: Both the percentage of the population aged 65+ and life expectancy at birth were consistently higher in OECD countries. Though both groups trended upward, the disparity with Non-OECD countries persisted*

- **Health Expenditure by % Population 65+ : OECD vs. Non-OECD (Year 2022)**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure2.3.png?raw=true" width="900" />

*Figure 2.3: The scatter plot shows a positive correlation between the percentage of the population aged 65+ and health expenditure per capita. OECD countries consistently exhibit both higher aging percentages and significantly greater health spending*

**Key Insights**  
1. Global Aging: The world is experiencing a significant rise in its aging population, with the percentage of people aged 65 and above steadily increasing.
2. OECD/Non-OECD Gap: There is a clear difference between OECD and Non-OECD countries, with OECD nations having a higher proportion of older adults.
3. Aging and Health Expenditure: The increase in the aging population is correlated with higher health expenditure.

> "These trends of a rising global aging society, particularly prominent in OECD nations, and its correlation with increased health expenditure highlight the evolving landscape of healthcare. Within this context, pharmaceutical expense constitutes a significant portion of total health expenditure. Understanding this significant component is crucial for gaining deeper insights into overall health expenditure patterns, especially as we focus on OECD countries where the aging society is more pronounced”

---

## 3. OECD Focus: Pharmaceutical Spending

Pharmaceutical expenditure is identified as a key cost driver in the health sector. In OECD nations, pharmaceuticals account for a significant proportion of total health spending, and this expenditure tends to grow in correlation with the percentage of the population aged 65 and over. However, the data also reveals several outliers, where certain countries exhibit unusually high pharmaceutical spending relative to their demographic structure.

- **Accumulated Pharmaceutical Expenditure as % of Total Health Expenditure (2010-2022) by Country**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure3.1.png?raw=true" width="900" />

*Figure 3.1: Approximately one-third of the countries shown allocate 20% or more of their total health spending to pharmaceuticals. Notably, the top-ranking countries—including Hungary, Poland, and Lithuania—dedicate over 45% of their total health expenditure to pharmaceutical costs*

- **Trend of % Population ages 65+ and Pharmaceutical Expenditure per Capita : OECD (2010-2022)**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure3.2.png?raw=true" width="900" />

*Figure 3.2: Pharmaceutical expenditure per capita rose along with the percentage of the population aged 65 and above, suggesting a potential relationship between these two trends.*

- **Pharmaceutical Expenditure by GDP and % Population 65+ (Year 2022)**

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure3.3.png?raw=true" width="900" />

*Figure 3.3: From the plot, we can observe a general trend that as GDP per capita increases, pharmaceutical expenditure per capita also tends to increase. This is supported by the upward sloping regression line. Additionally, countries with a higher percentage of their population aged 65 and above tend to have higher pharmaceutical expenditure per capita, as indicated by the larger bubbles generally appearing higher on the plot, especially among higher GDP countries. However, there are several prominent outliers such as USA: Has a very high GDP and the highest pharmaceutical expenditure per capita, exceeding the trend line significantly. >>highest R&D in OECD 57% of OECD https://www.oecd.org/en/publications/2021/11/health-at-a-glance-2021_cc38aa56/full-report/component-83.html#figure-d1e14193.<<
Japan: While having the highest aging population percentage, its pharmaceutical expenditure is high but not as exceptionally high as the USA's, especially considering its aging demographic. >>highest pharmacist but pharmaceutical expenditure is not that high <<
Luxembourg: Has a very high GDP but relatively lower pharmaceutical expenditure compared to other countries with similar or even lower GDPs. 

**Key Insights**  
1. Significant Proportion of Health Spending: Pharmaceutical expenditure constitutes a significant proportion of total health spending.
2. OECD Trends: In OECD countries, pharmaceutical spending per capita is increasing, which correlates with the rise in the aging population.
3. Aging, Wealth, and Spending: Countries with both a higher percentage of older adults and higher GDP per capita tend to have higher pharmaceutical expenditure per person.
4. Notable Outliers: 

> "Within OECD countries between 2010 and 2022, a clear trend exists where pharmaceutical expenditure per capita rises along with the percentage of the population aged 65 and above. Although pharmaceutical spending is a significant component of total health expenditure, according to the OECD, the primary driver of growth is not retail pharmaceuticals, but rather hospital pharmaceuticals [OECD Data Source]. Consequently, population aging alone may not be the key determinant; instead, variables like disease prevalence, national healthcare policies, and the availability of advanced, costly drugs likely contribute substantially to a country's spending.”

---
## 4. Global Disease Burden Trends (GBD)

Understanding global disease burden patterns helps contextualize health spending priorities. This section examines DALYs trends across four major categories, highlighting temporal changes and regional disparities.

- **% of Disability-Adjusted Life Years (DALYs) by Disease Category in each Income Group (Year 2010–2021)**  

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure4.1.png?raw=true" width="900" />

*Figure 4.1: Stacked area chart showing the proportion of DALYs for Communicable, maternal, neonatal, and nutritional diseases (CMNN), Injuries, Non-communicable diseases (NCDs), and Other COVID-19 pandemic-related outcomes from 2010–2021, overlaid with trend lines to highlight temporal changes. CMNN burden decreases in high-income countries but remains high in LMICs; NCDs show a steady increase globally; Injuries remain relatively stable; COVID-related outcomes show a clear spike in 2020–2021.*

- **DALYs per 100,000 Population by Disease Category (Year 2021)**  
<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure4.2.png?raw=true" width="900" />

*Figure 4.2: Regional disparities highlight how different categories dominate in various contexts. Africa shows high CMNN burden, high-income regions are dominated by NCDs, and injuries/COVID impact varies across regions.*

**Key Insights**  
1. Epidemiological Transition: High-income countries increasingly face NCDs, while LMICs continue to struggle with CMNN diseases.  
2. Injury Trends: DALYs from injuries remain stable or slightly declining, emphasizing the importance of preventive measures and safety systems.  
3. Shock Events: COVID-19 illustrates how sudden events can dramatically alter disease burden composition.  
4. Policy Implications: Disease burden composition shapes resource allocation and health policy priorities, ensuring interventions match regional needs and demographic profiles.

> “Global disease burden trends reveal a dual challenge: low- and middle-income countries must continue addressing communicable and maternal-child health issues, while high-income societies face a rising burden of chronic diseases. Injuries remain an important concern, and COVID-19 highlights the impact of unexpected shocks. The stacked area with trend lines allows us to see both the composition and temporal patterns of DALYs, providing a clear picture of how disease priorities vary across regions and over time. Understanding these patterns is essential for guiding strategic health investment and preparing resilient health systems tailored to each region’s needs.”

---

## 5. Linking Disease Burden to Spending

After examining global disease burden and regional disparities, the next step is to see how countries respond through health spending. This section explores total health expenditure globally, trends over time by income group, and pharmaceutical spending in OECD countries, linking disease burden to financial investment.

- **Global Regression: DALYs vs Health Expenditure per Capita (Year 2010–2021)**  

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure5.1.png?raw=true" width="900" />

*Figure 5.1: Scatter plot with regression lines showing the relationship between DALYs and health expenditure per capita across countries. Low-income countries experience high disease burden with limited spending, whereas high-income countries show lower DALYs with higher expenditure. Separate trend lines illustrate differences in responsiveness across income groups.*

- **DALYs & Health Expenditure Trend per Income Group (Year 2010–2021)**  

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure5.2.png?raw=true" width="900" />

*Figure 5.2: Trends of DALYs (left) and health expenditure per capita (right) from 2010–2021, shown as separate graphs by income group. The visualization highlights how disease burden and spending evolve differently over time across income levels, reflecting differences in effectiveness and resource allocation.*

- **OECD: NCD DALYs vs Pharmaceutical Expenditure with Aging Impact (Year 2010–2021)**  

<img src="https://github.com/polyst08/pandasproject-healthexpenditure/blob/main/Figure-Section01-04-05/Figure5.3.png?raw=true" width="900" />

*Figure 5.3: Bubble chart + line overlay for OECD countries. Bubble size and color represent %65+ population. Pharmaceutical expenditure rises with aging, while NCD DALYs trend over time, illustrating the “double pressure” of aging populations and rising drug costs.*

**Key Insights**  
1. Global Inequities: Low-income countries face high DALYs but limited health expenditure, highlighting gaps in access and resource allocation.  
2. Income Group Differences: Trend lines show that disease burden and spending evolve differently over time; higher-income countries tend to reduce burden with increased spending, while lower-income countries remain constrained.  
3. OECD Focus: Aging populations strongly influence pharmaceutical spending, which can dominate total health expenditure.  
4. Outliers: Certain OECD countries spend disproportionately on pharmaceuticals relative to NCD DALYs, signaling potential inefficiencies or policy challenges.  
5. Policy Implications: Aligning spending with disease burden and demographic pressures is essential. OECD countries must balance aging-related NCD care with sustainable pharmaceutical investment, while low- and middle-income countries should prioritize investment where disease burden is high.
 
>“Linking disease burden to health expenditure by income group uncovers stark contrasts. Low-income countries bear high disease burden with limited resources, whereas high-income countries reduce burden through higher spending. Trends over time demonstrate that income level affects both the magnitude and efficiency of spending. In OECD nations, aging populations and rising pharmaceutical costs create a “double pressure,” reinforcing the need for targeted, efficient, and sustainable health investment strategies. This section bridges the lens of health outcomes (DALYs) to financial inputs, guiding both global and country-specific policy decisions.”

---

## 6. Conclusion & Policy Implications

**Key Takeaways**  
- High-income countries invest more in health and reduce disease burden more effectively than low-income countries.  
- Aging populations drive both health expenditure and pharmaceutical spending, particularly in OECD nations.  
- Disease burden composition (CMNN, NCDs, Injuries, COVID) shapes health policy priorities and resource allocation.  
- Strategic investment must align with demographic trends and disease burden to ensure sustainable health outcomes.  

**Policy Implications**  
- Low- and middle-income countries: Target investment to reduce high disease burden efficiently.  
- OECD/high-income countries: Manage aging-related pressures and rising pharmaceutical costs with sustainable policies (e.g., drug pricing, reimbursement strategies).  
- Global perspective: Allocate resources based on disease burden composition and demographic context to maximize impact and efficiency.
