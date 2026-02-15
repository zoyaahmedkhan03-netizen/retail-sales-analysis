Retail Sales Analysis & Customer Segmentation

Business Problem: Analyzed UK online retail dataset to uncover revenue drivers and customer behavior patterns - every company's top priority.

Key Insights:
£8,718,510 total revenue across 397K cleaned transactions (Pandas ETL)
89% revenue from United Kingdom - geographic concentration risk
Top 20% customers generate 65% revenue (Pareto Principle confirmed via RFM + K-Means)
Festive season spikes visible in monthly trends (World Cup 2010 impact)
4 customer segments identified: Champions, At-Risk, Lost, Newbies

End-to-End Workflow:
├── Data Ingestion: 541K raw Excel → 397K cleaned CSV
├── ETL: Removed cancellations (12%), nulls, negatives
├── EDA: Top products, trends, country analysis (Matplotlib)
├── RFM Modeling: Recency/Frequency/Monetary features
├── ML: K-Means clustering (4 segments, Scikit-learn)
└── Visualization: Interactive Plotly dashboards (hover/zoom)
