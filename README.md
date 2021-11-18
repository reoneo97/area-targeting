# Area Targeting


This repository contains code used to perform area targeting calculations for **CN4205R: Pinch Analysis and Process Integration**

# How to Use

The Jupyter Notebook `main.ipynb` contains the code required to run the area targeting calculations. The input to the program is a .csv file which contains the necessary stream data. Below is the sample of the stream data format 

```
Stream Name,Supply,Target,Cp,U
Cooled Product-1,363.4,171.32,6.391,0.748590663
Cooled Product-2,171.32,89,32.083,0.748590663
Cooled Water Stream,165.3,30,3.42,2.34295
```

One important note is that streams provided in the stream data **has to contain utility streams and is balanced** ($\Delta H = 0$)

Once stream data is provided running all the cells in the notebook will return the total area required for that particular stream data configuration.