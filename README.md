# IKEA-Quantitative-Analysis
Quantitative reasoning of IKEA dataset 

This dataset from Saudi Arabia IKEA store 

[The scraped website link](https://www.ikea.com/sa/en/cat/furniture-fu001/)

The Prices are in saudi riyal

## Content

item_id : item id wich can be used later to merge with other IKEA dataframes

name: the commercial name of items

category:the furniture category that the item belongs to (Sofas, beds, chairs, Trolleys,…)

Price: the current price in Saudi Riyals as it is shown in the website by 4/20/2020

old_price: the price of item in Saudi Riyals before discount

Short_description: a brief description of the item

full_Description: a very detailed description of the item. Because it is long, it is dropped from the 
final dataframe, but it is available in the code in case it needs to be analyzed.

designer: The name of the designer who designed the item. this is extracted from the full_description column.

size: the dimensions of the item including a lot of details.As a lot of dimensions mentioned and they vary from item to item,
the most common dimensions have been extracted which are: Height, Wideh, and Depth. This column is dropped from the final dataframe, but it is available in the code in case it is needed.

width: Width of the item in Centimeter

height: Height of the item in Centimeter

depth: Depth of the item in Centimeter

sellable_Online: if the item is available for online purchasing or in-stores only (Boolean)
other_colors: if other colors are available for the item, or just one color as displayed in the website (Boolean)

link: the web link of the item

## Quantitative Analysis

- The category with name PAX has highest price

- The designer Ehlén Johansson has highest price 

- Sofas&Armchairs have highest price

- So if a highest price product is to be released then it should have then it should have the above attributes

- The price is highly dependent on volume

- The volume 0.7 has highest price
