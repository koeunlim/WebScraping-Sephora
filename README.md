# WebScraping-Sephora
NYCDSA web scraping project


## Table of Contents
[Directory Structure](#Directory-Structure)<br>
[Project Description](#Project-Description)<br>
[Data Description](#Data-Description)<br>
-[Source](#Source)<br>
[Data Visualization](#Data-Visualization)<br>
[Conclusion](#Conclusion)<br>


## Directory Structure
```
.
├── WebScraping-Sephora
    ├── 00_Sephora_getProductURLs.ipynb
    ├── 01_Sephora_getReviews.ipynb
    ├── 02_Sephora_EDA.ipynb
    ├── data
        ├── product_urls.csv
        ├── product_info0.csv
        ├── ...
        ├── product_info462.csv
    ├── plots
        ├── 
    ├── README.md
```


## Project Description


## Data Description
name of the column|description|break down|
|---|---|---|
|Product|the name of the product as listed||
|Category|category the product|foundation-makeup, lipstick||
|URL|the original URL gathered with selenium||
|Price|the price listed in dollars||
|UserName|nickname of the reviewer||
|UserID|author ID number of the reviewer||
|Rating|number of stars|4, 5||
|Eyecolor|eyecolor of the reviewer|blue, brown, green, gray, hazel||
|Haircolor|haircolor of the reviewer|blonde, brunette, auburn, black, red, gray||
|Skintone|skintone of the reviewer|porcelain, fair, light, medium, tan, olive, deep, dark, ebony||
|SwatchID|swatch ID number of the product||
|R|red scalar from the swatch's RGB|0~255||
|G|green scalar from the swatch's RGB|0~255||
|B|blue scalar from the swatch's RGB|0~255||



### Source
Product data were gathered from [Sephora](https://www.sephora.com/)
Product review data were gathered from [Bazaarvoice](https://api.bazaarvoice.com)

## Data Visualization


## Conclusion