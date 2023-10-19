This notebook explains the different data pre-processing techniques necessary in the initial phase of data engineering. The dataset contains a large number of NULL values that must be dealt with before any analysis can be performed. The first step is to clean the data. The missing/NULL values in the dataset are handled using the pandas library's functions. Further encoding is done to handle different types of categorical attributes followed by detection and removal of outliers.<br>
[Dataset](https://www.kaggle.com/anthonypino/melbourne-housing-market?select=Melbourne_housing_FULL.csv) <br>
### Attributes
1. Suburb: Suburb
2. Address: Address
3. Rooms: Number of rooms
4. Price: Price in Australian dollars
5. Method:
- S - property sold;
- SP - property sold prior;
- PI - property passed in;
- PN - sold prior not disclosed;
- SN - sold not disclosed;
- NB - no bid;
- VB - vendor bid;
- W - withdrawn prior to auction;
- SA - sold after auction;
- SS - sold after auction price not disclosed.
- N/A - price or highest bid not available.

6. Type:
- br - bedroom(s);
- h - house,cottage,villa, semi,terrace;
- u - unit, duplex;
- t - townhouse;
- dev site - development site;
- o res - other residential.

7. SellerG: Real Estate Agent
8. Date: Date sold
9. Distance: Distance from CBD in Kilometres
10. Regionname: General Region (West, North West, North, North east …etc)
11. Propertycount: Number of properties that exist in the suburb.
12. Bedroom2 : Scraped # of Bedrooms (from different source)
13. Bathroom: Number of Bathrooms
14. Car: Number of carspots
15. Landsize: Land Size in Metres
16. BuildingArea: Building Size in Metres
17. YearBuilt: Year the house was built
18. CouncilArea: Governing council for the area
19. Lattitude: Self explanitory
20. Longtitude: Self explanitory
