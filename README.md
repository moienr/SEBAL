# SEBAL: Surface Energy Balance Algorithms for Land - Evapotranspiration Computation
**Class of Remote Sensing of Water, Soil and Vegetation - `Dr. Saeid Hamzeh`**

by: `Moien Rangzan`
moienrangzan@gmail.com
## Calculating Surface Radiation Balance Equation for Rn - Landsat C2 Level 1
[Sebal_Rn_Level1.ipynb](https://github.com/moienr/SEBAL/blob/main/Sebal_Rn_Level1.ipynb)

Implementaion Based on the [SEBAL IDAHO](https://www.posmet.ufv.br/wp-content/uploads/2016/09/MET-479-Waters-et-al-SEBAL.pdf)



## Calculating the ESUN values for Landsat 8 Level 2 products
[Sebal_Reflectance_Albedo_calculation.ipynb](https://github.com/moienr/SEBAL/blob/main/sebal_Reflectance_Albedo_calculation.ipynb)

Since Sebal needs ESUN and Albedo to be calulted, and these values are not provided in the L2 Products, I wrote this Notebook to better understand the derivation on these values.


These are the ESUN values for Landsat8, that I drove:

| esun2 | esun3 | esun4 | esun5 | esun6 | esun7 |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|2019.779|1861.274|1569.382|960.346|238.835|80.501|

**NOTE:** The ESUN values change every 11 years due to the sun's positioning, so if you are seening this repo in 11 years from now, I think it would be wise to rerun this notebook :))