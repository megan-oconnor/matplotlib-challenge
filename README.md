# matplotlib-challenge
module 5 challenge

## Analysis
- 2 treatments with the lowest Tumor Volume (mm3) median have relatively similar variation: Capomulin (41.6 and 24.95) and Ramicane (40.7 and 23.5)
- The treatment with the largest Tumor Volume (mm3) median was Ketapril. It also had the largst variation  at 68.6.

### Analysis of Final Tumor Size for Capomulin, Ramicane, Infubinol, Ceftamin
Spread of final tumor size:
![iqr and median table](https://github.com/megan-oconnor/matplotlib-challenge/blob/main/Images/final_tumor_iqr_median_table.png)

### Capomulin Analysis
In the anaysis of one mouse on this drug regimen, the size of the tumor decreased over time.
![single mouse analysis](https://github.com/megan-oconnor/matplotlib-challenge/blob/main/Images/capomulin_mouse_r554.png)

When looking at the mice that had this drug regimen, it looks like weight was a factor in the size of the tumor.
27.6% of the variation in Tumor Volume (mm3) can be explained by the mouse's Weight (g).
**The linear regression model found for this drug regimen: Tumor Volume (mm3) = 0.96*[Weight (g)] + 21.49**
![weight and tumor size spread for capomulin](https://github.com/megan-oconnor/matplotlib-challenge/blob/main/Images/capomulin_weight_to_tumor_volume.png)


## Resources
- Code File: [main.ipynb](https://github.com/megan-oconnor/matplotlib-challenge/blob/main/main.ipynb) contains analysis of the dataset, contained in the Pymaceuticals folder
- Datasets: 1 datasets for mouse data, located in the [data](https://github.com/megan-oconnor/matplotlib-challenge/tree/main/data) folder
- Images: contain screenshots of the datatables from the analysis, all located in the [Images](https://github.com/megan-oconnor/matplotlib-challenge/tree/main/Images) folder
