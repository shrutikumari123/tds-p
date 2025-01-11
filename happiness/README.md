# Automated Analysis Report

## Summary
{'columns': ['Country name', 'year', 'Life Ladder', 'Log GDP per capita', 'Social support', 'Healthy life expectancy at birth', 'Freedom to make life choices', 'Generosity', 'Perceptions of corruption', 'Positive affect', 'Negative affect'], 'data_types': {'Country name': dtype('O'), 'year': dtype('int64'), 'Life Ladder': dtype('float64'), 'Log GDP per capita': dtype('float64'), 'Social support': dtype('float64'), 'Healthy life expectancy at birth': dtype('float64'), 'Freedom to make life choices': dtype('float64'), 'Generosity': dtype('float64'), 'Perceptions of corruption': dtype('float64'), 'Positive affect': dtype('float64'), 'Negative affect': dtype('float64')}, 'missing_values': {'Country name': 0, 'year': 0, 'Life Ladder': 0, 'Log GDP per capita': 28, 'Social support': 13, 'Healthy life expectancy at birth': 63, 'Freedom to make life choices': 36, 'Generosity': 81, 'Perceptions of corruption': 125, 'Positive affect': 24, 'Negative affect': 16}, 'summary_stats': {'Country name': {'count': 2363, 'unique': 165, 'top': 'Lebanon', 'freq': 18, 'mean': nan, 'std': nan, 'min': nan, '25%': nan, '50%': nan, '75%': nan, 'max': nan}, 'year': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 2014.7638595006347, 'std': 5.059436468192795, 'min': 2005.0, '25%': 2011.0, '50%': 2015.0, '75%': 2019.0, 'max': 2023.0}, 'Life Ladder': {'count': 2363.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 5.483565806178587, 'std': 1.1255215132391925, 'min': 1.281, '25%': 4.647, '50%': 5.449, '75%': 6.3235, 'max': 8.019}, 'Log GDP per capita': {'count': 2335.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.399671092077089, 'std': 1.1520694444710216, 'min': 5.527, '25%': 8.506499999999999, '50%': 9.503, '75%': 10.3925, 'max': 11.676}, 'Social support': {'count': 2350.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.8093693617021277, 'std': 0.12121176420299144, 'min': 0.228, '25%': 0.744, '50%': 0.8345, '75%': 0.904, 'max': 0.987}, 'Healthy life expectancy at birth': {'count': 2300.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 63.40182826086957, 'std': 6.842644351828009, 'min': 6.72, '25%': 59.195, '50%': 65.1, '75%': 68.5525, 'max': 74.6}, 'Freedom to make life choices': {'count': 2327.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.750281908036098, 'std': 0.13935703459253465, 'min': 0.228, '25%': 0.661, '50%': 0.771, '75%': 0.862, 'max': 0.985}, 'Generosity': {'count': 2282.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 9.772129710780206e-05, 'std': 0.16138760312630687, 'min': -0.34, '25%': -0.112, '50%': -0.022, '75%': 0.09375, 'max': 0.7}, 'Perceptions of corruption': {'count': 2238.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.7439709562109026, 'std': 0.1848654805936834, 'min': 0.035, '25%': 0.687, '50%': 0.7985, '75%': 0.86775, 'max': 0.983}, 'Positive affect': {'count': 2339.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.6518820008550662, 'std': 0.10623970474397627, 'min': 0.179, '25%': 0.572, '50%': 0.663, '75%': 0.737, 'max': 0.884}, 'Negative affect': {'count': 2347.0, 'unique': nan, 'top': nan, 'freq': nan, 'mean': 0.27315083084789094, 'std': 0.08713107245795021, 'min': 0.083, '25%': 0.209, '50%': 0.262, '75%': 0.326, 'max': 0.705}}}

## Story
The dataset analyzed provides insights into happiness levels across various countries, covering the years 2005 to 2023. It includes several indicators that contribute to a country's happiness, such as economic factors, social support, health, and perceptions of freedom and corruption.

Here’s a comprehensive narrative based on the analysis of the dataset:

### Overview
The dataset consists of 2,363 records spanning multiple countries and contains vital statistics such as "Life Ladder" scores — which represent subjective well-being — along with socioeconomic indicators like "Log GDP per capita" and levels of "Social support." The dataset encourages a multi-faceted interpretation of happiness, illustrating the complexity behind this seemingly simple metric.

### Key Variables
1. **Country Name**: The dataset encompasses 165 unique countries, with Lebanon being the most frequently represented nation (18 times).
2. **Year**: Data ranges from 2005 to 2023, with an average year of approximately 2015, indicating a temporal focus on more recent data.
3. **Life Ladder**: The average score here is approximately 5.48, with a standard deviation of about 1.13, showing a range from 1.28 (low happiness) to 8.02 (high happiness). This metric serves as a central measure for wellbeing, demonstrating variance among countries.
4. **Log GDP per Capita**: With a mean value of 9.4, the economic aspect correlates strongly with happiness, albeit a few missing values (28 entries) may indicate underreporting or data collection challenges in specific years or countries.
5. **Social Support**: The mean social support score stands at 0.81, highlighting the perceived availability of assistance in times of need. With 13 missing entries, it shows good coverage but a need for cautious interpretation.
6. **Healthy Life Expectancy at Birth**: Averaging 63.4 years indicates general health and longevity across countries, although there are significant missing values (63 entries), which may skew the comprehensive understanding of health impacts on happiness.
7. **Freedom to Make Life Choices**: An indicator of personal agency, the average score of 0.75 shows that most individuals in the dataset feel they have a degree of control over their life choices.
8. **Generosity**: Strikingly, the average score is nearly 0, suggesting widespread low levels of reported generosity in the dataset, with 81 missing entries.
9. **Perceptions of Corruption**: The mean of 0.74 emphasizes that perceptions of corruption significantly impact happiness, with more missing data (125 entries) reflecting perhaps the inconsistency in such assessments globally.
10. **Positive and Negative Affect**: Scores for positive affect (mean of 0.65) and negative affect (mean of 0.27) support the narrative that countries generally experience higher positive experiences relative to negative ones, although these factors remain intertwined with context.

### Observations of Missing Values
Notably, various attributes show missing values, indicating potential gaps in data collection:
- **Generosity** (81 missing)
- **Perceptions of Corruption** (125 missing)
- **Healthy Life Expectancy** (63 missing)
  
These gaps may hinder a holistic understanding of how each factor interplays with happiness, suggesting areas for future data collection or refinement in methodologies.

### Conclusion and Recommendations
The analysis suggests that while economic and social factors are critical to understanding happiness, the subjective nature of well-being—as represented by metrics like the Life Ladder—demands a nuanced approach. Given the observed correlation between different scores and reported happiness, future studies could enhance the dataset by focusing on areas with higher missing values to better analyze the impact of various factors on life satisfaction.

It is recommended to extend this analysis further by incorporating time-series analyses to observe trends over the years, and by exploring how different cultural contexts impact the relationships between these various factors and perceived happiness.

## Visualizations
![Visualization](C:\Users\shruti kumari\Desktop\tds\happiness\heatmap.png)
