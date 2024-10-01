# International Trade Network Analysis

## Abstract

This study examines the recent developments in the international trade network, focusing on key players, trade patterns, and the effects of the COVID-19 pandemic. It provides a descriptive analysis of the network in 2021, highlighting significant commercial relationships between countries and excluding minor trade flows. The main findings include:  
1. Most countries maintain close connectivity in the global trade network, regardless of their specific trade partnerships.  
2. Bridging roles are primarily held by countries above a certain threshold of connections.  
3. The United States, China, and Germany remain the most influential actors within the network.  
4. The network consists of seven distinct communities, each led by a highly interconnected country.

## Project Overview

### I. Introduction

The study begins by presenting an updated overview of the international trade network, considering key actors, trade behaviours, and the repercussions of the COVID-19 pandemic on global commerce. Our analysis is based on the top five trading partners of each country, filtering out noisy trade flows and focusing on significant connections.

### II. Literature Review

Recent literature has highlighted the dominance of a small group of countries in global trade and the presence of distinct communities within the international trade network. Studies using Social Network Analysis (SNA) have consistently identified the US, China, and Germany as central players, with persistent communities despite global disruptions like the COVID-19 pandemic.

### III. Contribution

This work provides an updated perspective by analysing trade data from 2021 and focusing on the top trading partners of each country. This approach allows for a clearer understanding of meaningful trade relationships, unaffected by extreme export flows, and highlights the impact of recent global events on the trade network structure.

### IV. Data and Methodology

The study uses trade data from the World Integrated Trade Solution (WITS) for 2021, focusing on the "Export - Trade (US$ Mil)-Top 5 Export Partner" indicator. We treat the trade network as an undirected network, where countries act as nodes and substantial trade relationships are represented as edges.

#### Network Metrics Used:
- **Degree Centrality**: Measures the volume of trade flow.
- **Closeness Centrality**: Reflects the connectivity of countries within the trade network.
- **Betweenness Centrality**: Identifies countries acting as bridges in global trade.

We also use the Louvain algorithm to detect community structures and understand the formation of trade groups.

### V. Analysis

The international trade network in 2021 comprises 160 nodes and 518 edges. Key actors like the US, China, and Germany maintain high degree centrality and are leaders in their respective communities. The Louvain algorithm revealed seven communities, each led by a core country driving trade interactions in its region.

### VI. Limitations and Future Research

Data availability and reporting limitations pose challenges in analysing international relations. The omission of longitudinal and sector-specific trade patterns limits the scope of this study. Future research could expand to include these dimensions and explore directed and weighted network methodologies for deeper insights.

### VII. Conclusion

The study highlights the resilience of the international trade network post-COVID-19, with the US, China, and Germany maintaining their dominance. Trade communities remain stable, reflecting a high degree of reciprocity and geographical proximity in trade relations.

## How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/international-trade-network-analysis.git
   cd international-trade-network-analysis
   ```

## Dataset

- **Source:** World Integrated Trade Solution (WITS) 2021
- **Indicator Used:** "Export - Trade (US$ Mil)-Top 5 Export Partner"
- **Description:** Trade data focused on each country’s top five export partners in 2021.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to enhance the project.


## References

- Antonietti, R., Falbo, P., Fontini, F. & Grassi, R., 2022. *The world trade network: country centrality and the COVID-19 pandemic*. Applied Network Science, pp. 7-18.  
- Gönçer-Demiral, D. & Ince-Yenilmez, M., 2022. *Network analysis of international export pattern*. Springer Nature.  
- Herman, P., 2022. *Modeling complex network patterns in international trade*. Rev World Econo 158, pp. 127-179.  
- Kiyota, K., 2022. *The COVID-19 pandemic and the world trade network*. Journal of Asian Economics, Volume 78.  
- Krugman, P. R., Obstfeld, M. & Melitz, M. J., 2023. *International Trade Theory and Policy*. Twelfth Edition ed. Pearson.  
- Newman, M., 2018. *Networks*. Second Edition ed. New York: Oxford University Press.  
- Rothman, S. B., 2007. *Understanding Data Quality through Reliability: A Comparison of Data Reliability Assessment in Three International Relations Datasets*. International Studies Review, 9(3), pp. 437-456.  
- Smith, M. & Sarabi, Y., 2022. *How does the behaviour of the core differ from the periphery? - An international trade network analysis*. Elsevier, pp. 1-15.  
- Vidya, C. T. & Prabheesh, K. P., 2020. *Implications of COVID-19 Pandemic on the Global Trade Networks*. Emerging Markets Finance and Trade, Volume 56:10, pp. 2408-2421.  
- WITS. 2021. *Data Download*. Accessed 23 February 2024. [WITS Data Download](https://wits.worldbank.org/datadownload.aspx?lang=en).
