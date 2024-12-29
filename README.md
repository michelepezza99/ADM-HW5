# ADM-HW5

+ **main.ipynb:** [Link](https://github.com/michelepezza99/ADM-HW5/blob/main/main_final.ipynb)

# Homework 5 - USA Airport Flight Analysis  

<p align="center">
  <img src="https://gtm-24.de/wp-content/uploads/2019/11/GTM-24-55.jpg">
</p>

---

## Project Overview  

In this homework, we analyze the **USA Airport Dataset** to investigate the structure and behavior of the U.S. flight network. Our focus is on understanding network connectivity, identifying key hubs, finding optimal routes, and exploring strategies for partitioning and community detection.  

We approach the problem using graph theory, optimization techniques, and distributed computing frameworks to provide insights into network dynamics and operational efficiency.  

---

## Key Tasks  

1. **Flight Network Analysis**  
   - We examine network size, density, and degree distributions.  
   - We identify hubs and analyze passenger traffic patterns.  
   - Interactive visualizations highlight the structure and busiest routes.  

2. **Nodes' Contribution**  
   - We compute centrality measures to determine the importance of each airport.  
   - Comparisons across metrics reveal influential nodes and connectivity trends.  

3. **Finding Best Routes**  
   - Using Dijkstra’s algorithm, we identify the shortest and most efficient routes between cities.  
   - We account for multiple airports and optimize paths based on distance.  

4. **Network Partitioning**  
   - We simulate the division of the network into two disconnected subgraphs.  
   - Karger’s Minimum Cut algorithm identifies critical edges for separation.  

5. **Community Detection**  
   - We detect clusters of airports using Louvain’s method and compare results with alternatives like Spectral Clustering.  
   - Visualizations illustrate the community structure within the network.  

---

## Additional Components  

- **Connected Components with MapReduce**  
  We compare a custom MapReduce implementation with GraphFrames for identifying connected components. While both methods yield the same results, GraphFrames achieves a **77x speedup**, demonstrating its efficiency.  

- **Algorithmic Question: Optimal Paths with Constraints**  
  We implement and optimize Dijkstra’s algorithm to find the cheapest routes with a maximum number of stops. Alternative solutions suggested by LLMs are explored and evaluated.  

---

## Technologies Used  

- **Python**: Data processing and network analysis.  
- **PySpark**: Distributed computing and MapReduce implementation.  
- **GraphFrames**: Optimized graph processing.  
- **NetworkX**: Graph visualizations and algorithm testing.  
- **LLMs**: Enhancements and optimizations for algorithms.  

---

## Final Remarks  

This project demonstrates how network analysis techniques can be applied to model and optimize transportation systems. By leveraging distributed computing and advanced algorithms, we explore the challenges and opportunities within flight networks, offering insights into connectivity, efficiency, and resilience.  
