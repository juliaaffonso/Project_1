# Project_1

## What's this?

This is an analysis of unfinished public projects in Brazil, using data from the Federal Court of Accounts, which is released annually.

The goal here was to uncover trends and costs. To achieve this, I used the following Python libraries: pandas, os, re, and unidecode.

## Findings

Exploring this data, I found that Brazil had 11,469 unfinished projects as of April 2025 — the date when the latest information was released.

Maranhão was the state with the highest number of unfinished projects.

I also compared the data on halted projects with the Human Development Index (HDI) of each Brazilian state. I found that several states with a higher number of unfinished projects also have lower HDI scores.

Since the Federal Court of Accounts published this data in April 2025, the situation may have changed. Some projects may have resumed, while others might have been added to the list of unfinished works.

## Data Collection

All dataframes on halted projects are available at the following link:
https://paineis.tcu.gov.br/pub/?workspaceId=8bfbd0cc-f2cd-4e1c-8cde-6abfdffea6a8&reportId=013930b6-b989-41c3-bf00-085dc65109de&filterPaneEnabled=false&navContentPaneEnabled=false

The Human Development Index (HDI) data can be found here:
http://www.atlasbrasil.org.br/ranking

## Data Analysis Process

Because the dataframe contains chunks of descriptive information, it took me some time to clean the data — removing accents, special characters, and extra spaces.

The tables also have different identification numbers, which made it harder to determine which ones were best to use.

## Approaches

This was the first time I needed to use the .melt() function to transform a dataframe from wide to long format. I also practiced using regular expressions.

I created all the charts in Datawrapper. Unfortunately, I couldn’t find a histogram option there, so I left the webpage without one.

## Next Steps

In the future, I plan to use AI classification to label the reasons why public projects remain unfinished and to categorize the types of work. Both columns contain extensive descriptive information that I wasn’t able to process this time.


