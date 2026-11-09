# hcde-410-final

#

# A4

## AI Usage:
I did not use AI for this assignment.

## Motivation & problem
I want to learn how well different languages are represented in online information, and whether people who speak certain languages may have more or less access to information online than others. I chose to look specifically at Wikipedia, as it is commonly used online to learn about information on topics, so I want to see if there are gaps between how many people speak a language and how much Wikipedia content exists in it to show where information access is unequal. I hope to learn which languages are most underrepresented based on speaker population, and which are overrepresented. I understand that this analysis does not mean that certain languages have more or less representation in online information, as I am only looking at Wikipedia.

## Data
— the dataset(s), what they contain, a link, the license/terms, why they fit, and any ethical considerations.

### Wikipedia
The dataset I will be looking into is the List of Wikipedia statistics, it is open source and contains data for each language's Wikipedia, including language, articles, pages, edits, files, admins, users, and files. The data in the table comes from Data:Wikipedia statistics/data.tab It contains data on all Wikipedia sites, including active users, admins, articles, edits, files, pages, and users.

The license says that the data available falls under Creative Commons Zero.

This dataset fits what I am trying to explore because I want to see how Wikipedia is representing languages based on how much information/articles are available to speakers of certain languages.

The ethical consideration here is that it doesn't contain personal user data, only user activity. The risks are that the number of articles per language may be misinterpreted, such as numbers being inflated due to bot postings, or a low amount of content specifically on Wikipedia in a language may be due to users of that language using a different site and not due to a lack of information. To be transparent, I will state uncertainty around the statistics and avoid concluding that any language is lacking information online. I will only talk about what I observed with the Wikipedia dataset.

### LinguaMeta
The dataset I will be using to compare this data with is Google's LinguaMeta, which includes data on total speakers and speakers by locale for each language. It is open source and estimates the speakers per language by country using several data sources such as CLDR Unicode, Google Research, IETF, Wikidata, and Wikipedia.

The license says that the data available falls under the Creative Commons Zero

The ethical consideration is that the data contains no personal information. But the risks could be misrepresentation, as speaker counts are only estimates that may not accurately represent how many actual speakers of that certain language there are. To be transparent, I will state uncertainty around the statistics and avoid making conclusions about any specific language’s knowledge or access to knowledge.

## Unknowns & dependencies
The LinguaMeta Repository says it has been archived, which could mean that it is no longer being updated or the data is unable to be accessed fully. I also have not imported the tsv file yet so I am not exactly sure if there will be issues when accessing it.

For the Wikipedia dataset, because it is constantly being updated as it uses MediaWiki's API to automatically calculate and change the dataset, so I need to make sure that I download the data to keep it from changing the calculations and analysis. Because it doesn't contain a direct tsv or csv file, I might need to manually create one.

Some unknowns could be if speakers of certain languages are actually being fully represented due to the estimates and if Wikipedia articles in a certain language actually accurately reflect how much representation a language actually has regarding information online.

## Feedback from class:
After talking about my draft, I received feedback about whether different languages have their own versions of Wikipedia and then maybe comparing those sites, unless I only want to look into Wikipedia. After discussing, I want to try to incorporate research into why a certain language has fewer articles or less representation on Wikipedia by seeing if they have other resources online. I also received feedback on how I am going to scope the project, and I am going to scope the languages based on the available languages already in Wikipedia.

