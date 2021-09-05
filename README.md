# Challenge-10

Crypto Clusters 

Our goal was to use unsupervised machine learning to clusters cryptocurrencies by their performance in different time periods.

1. We starting by importing Crypto Data into our note book, and turning it into a DataFrame .

2. We then found the optimal K to try so we we would have an idea of what the most efficent number of clusters would be.

3. We then put the sklearn model to work and graphed the results. 

4. Afterwards we filtered out some of the data we did not need using PCA.

5. We then put the model to work again on the filtered data.

6. Finally we compared results between the two

7. The filtered Data provided a cleaner picture of the clusters 




---

## Technologies
This application is written in Python 3.7

this application uses the following packages:
 
pandas
pyviz hvplot
pathlib
KMeans from sklearn 
PCA from sklearn
StandardScaler from sklearn

---

## Installation Guide

Before running the application first install the following dependencies.

python
- First item  conda install -c pandas
- Second item conda install -c pathlib
- Third item conda install -c sklearn
 


---

## Examples

Please see the following images of the code and resulting graphs 

![alt text for screen readers](/Images/K value code.jpg
 "Text to show on mouseover")Images/K value code.jpg

Images/elbow curve challenge 10.jpg

Images/final clusters.jpg
---

## Usage

To use the data simply clone the repository.

Different K values can be looked at to see if the clusters are more useful. Just because 4 is the most efficent it may not be the best.

Charts could also be changed to make things look different  
```
---

## Contributors

Sean Patel (myself) seanpatel076@gmail.com
---

## License

License is public anyone can use or make changes to this application
