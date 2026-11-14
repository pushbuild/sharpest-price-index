# Sharpest price index

Monthly price index of used and new hardware and collectibles sold on eBay US, from
[sharpest.ai](https://sharpest.ai/price-index). Updated weekly.

Need this data in your own tool or automated? [pushbuild.com/apis](https://pushbuild.com/apis/?utm_source=github&utm_medium=readme&utm_campaign=sharpest-price-index)

`price-index.csv` columns: `category, month, index, products, days_tracked`.
Each product's monthly median eBay price (item plus shipping) is rebased to its first tracked
month = 100; a category's index is the mean across its products. Method:
https://sharpest.ai/price-index

License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit "sharpest.ai price index" with a link.
