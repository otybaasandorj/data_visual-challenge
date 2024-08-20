# Pymaceuticals analysis

In the study of 249 mice who were identified with SCC tumors, we are comparing the performance of Pymaceuticals’ drug of interest, Capomulin with other treatment regimens over the course of 45 days. There was a duplicate mouse being recorded so after removing the duplicates and having 248 mice, we were able to plot the number of observed mouse timepoints of each of the 10 drug regimen to find that Capomulin as well as Ramicane have significantly higher number of observed mouse timepoints.
![pandas_bar](https://github.com/otybaasandorj/data_visual-challenge/blob/main/Pymaceuticals/images/pandas_bar.png)

Of the 248 mice, maybe the gender had something to do with certain drug regimens or total tumor volume but when shown on a graph, it was evident that the distribution between male and female mice were quite similar, indicating that gender might not have had a significant impact in this particular study.
![gender_pie](https://github.com/otybaasandorj/data_visual-challenge/blob/main/Pymaceuticals/images/gender_pie.png)

We narrowed the treatments to Capomulin, Ramicane,  Infubinol, and Ceftamin to examine outliers and discovered only Infubinol had potential outliers. While Capomulin and Ramicane both had significantly lower final tumor volumes, Infubinol and Ceftamin had higher volumes.
![boxplot](https://github.com/otybaasandorj/data_visual-challenge/blob/main/Pymaceuticals/images/boxplot.png)

Pymaceuticals' drug of interest is Capomulin so we ran an analysis for a single mouse, l509 treated with Capomulin. When we view the tumor volume (mm3) over the span of 45 days, we can see that the tumor volume (mm3) decreases as the days go by. Although not completely gone, there is a sharp decrease then a bit of an increase followed by another decrease. 
![line](https://github.com/otybaasandorj/data_visual-challenge/blob/main/Pymaceuticals/images/line.png)

The correlation between mouse weight and the average tumor volume of rat entire Capomulin regimen is 0.84 which suggests a very strong correlation. The larger the weight of the mouse (g), the larger the average tumor volume (mm3). 
![scatter_coefficient](https://github.com/otybaasandorj/data_visual-challenge/blob/main/Pymaceuticals/images/scatter_coefficient.png)
