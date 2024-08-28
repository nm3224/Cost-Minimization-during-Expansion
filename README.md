# Cost-Minimization-during-Expansion

### This is a personal project dealing with a business problem statement where the goal is cost minimization during expansion.
The client is a fast-growing company selling merchandise across the US. Their team believes that as the company expands, they may benefit from moving from a single distribution warehouse (currently located in Syracuse, NY) to multiple distribution points.

Their sales are growing at a rate of 15% a year, so their spend with their parcel service is exploding.
We have been given the following information:

1. The company pays the following rates:
* $5.60 / package for shipments < 500 miles
* $8.70 / package for shipments < 1250 miles
* $11.90 / package for shipments > 1250 US within the continental US $18.00 / package for shipments requiring air freight

2. The company ships packages in equivalent size and weight (you may assume all packages have the same price)

3. Shipments also have surcharges – the client has very little visibility into the reasons for these so they cannot share any information with you.

4. Their current warehousing spend is $150K a year.

### My solution presented an analysis of the current data as well as a breakdown of future savings opportunites for the company over time. The conclusions are listed below:

* In 5 years from now, another warehouse in CA is likely to save money. A single additional warehouse would save costs and hold long-term benefits.

* By opening a second warehouse, the company would save a grand total of $1.1M over the next 5 years.
     * That's 9.62% in total savings.
     * They would save $1.85M on shipping costs alone.

* Warehouse costs would be $1.5M over the next 5 years.

* Their net savings would be $654,309.64.

* They would be saving 17.29% on shipping, yearly.

### To run the code:

Set your file path by running the following line (replace with your repo location and folder name):
```
file_path = 'data/Shipping_Data.xlsx' shipping_data = pd.read_excel(file_path)
```

### Structure of Repo:

- `data/`: This includes our data file, `Shipping_Data.xlsx`.
- `states/`: Includes all files for the `states.shp` file used for mapping.
- `images/`: Includes all data visualizations created using our `.ipynb` file.
- `presentation/`: Includes powerpoint presentation, `.pdf` file of Python notebook and slide deck of final analysis, visualizations, and conclusions.
- `Cost-Minimization-during-Expansion.ipynb`: Python Jupyter `.ipynb` file for running all data analysis and visualizations.  
