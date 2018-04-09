# Exploring Gun Deaths in the US

The dataset comes from FiveThirtyEighty and can be found [here](https://github.com/fivethirtyeight/guns-data).

It contains information on gun deaths in the US from 2012 to 2014. Each row in the dataset represents a single fatality. The columns contain demographic and other information about the victim. Here is an explanation of each column:

* `--` - identifier column containing the row number
* `year` - the year in which the death occured
* `month` - the month in which the death occured
* `intent` - the intent of the perpetrator of the crime. It can be `Suicide`, `Accidental`, `NA`, `Homicide`, or `Undetermined`
* `police` - whether a police officer was involved in the shooting. `0` for false and `1` for true
* `sex` - the gender of the victim. `M` for male and `F` for female
* `race` - the race of the victim. Either `Asian/Pacific Islander`, `Native American/Native Alaskan`, `Black`, `Hispanic`, or `White`
* `hispanic` - a code indicating the Hispanic origin of the victim
* `place` - where the shooting occured. Either `Home`, `Street`, or `Other specified`
* `education` - educational status of the victim. Can be one of the following:
    * `1` - Less than High School
    * `2` - Graduated from High School or equivalent
    * `3` - Attended College
    * `4` - At least graduated from College
    * `5` - Not available
    
**The objective**: The objective is to find patterns in the demographics of the victims.

**Techniques used**
* Working with CSV files
* Dictionary mapping
* Working with rates to reduce bias
