# Ship Prediction System

## TFM KSchool

Autor: Francisco Mújica

Year: 2019

Edition: 

The files I have are too big.
I have 15 files corresponding to the 15 months.
With more than 90 fields and an average of 500,000 records.
The average weight of the files is 500 mega.

Due to the large amount of data, to make the prediction of shipments by destination, 
I have reduced the files to a first version with only three fields in each file.
We continue with an average of 500,000 records, but we are left with the fields of:

```
[Product cod]    : With code of type of service
[Origin Country] : With the country code of origin
[Destin Country] : With the country code of destination
```

With this data trimming, we have a weight of 68Megas between all the files

I have left a copy of these files in the [datos] folder, each file corresponds to a month.
These files do not have a date field between their fields, so once loaded and cleaned, 
i will add a date field, which will represent the year and month to which the data belongs.
