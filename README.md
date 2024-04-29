# Using the loc.gov API with the Chronicling America Historic Newspapers Collection
## About this Repository
This repository contains 4 Jupyter notebooks designed specifically for using the loc.gov API to access Chronicling America content. 
### Credits
The Jupyter notebooks in this repository were created by NDNP staff in the Serial and Government Publications Division at the Library of Congress. The content was inspired by, and at times closely follows, the notebooks created by [LC Maps for Robots](https://github.com/LibraryOfCongress/data-exploration/blob/861bbe6e0fb9992fe1c4fedf43e3f61bccd980bc/loc.gov%20JSON%20API/maps/README.md) 

- Contact ndnptech@loc.gov for questions about these Chronicling America notebooks.
---


## Chronicling America: Digital Collection of Historic American Newspapers
[**Chronicling America**](https://chroniclingamerica.loc.gov/) is a searchable and freely accessible digital collection of historic newspaper pages. A product of the National Digital Newspaper Program (NDNP), it contains millions of newspaper pages from nearly every state and territory in the United States published through 1963.

NDNP, a partnership between the National Endowment for the Humanities (NEH) and the Library of Congress, is a long-term effort to develop an Internet-based, searchable database of U.S. newspapers with descriptive information and select digitization of historic pages. Supported by NEH, this rich digital resource is developed and permanently maintained at the Library of Congress. An NEH award program will fund the contribution of content from, eventually, all U.S. states and territories.

More information on program guidelines, participation, and technical information can be found on the [**Chronicling America LibGuide**](https://guides.loc.gov/chronicling-america), [**Library of Congress: Chronicling America Collection**](https://www.loc.gov/collections/chronicling-america/about-this-collection/) and on the [**National Endowment for the Humanities website**](http://www.neh.gov/projects/ndnp.html).

### Note on Language in Chronicling America

Developing the most useful keywords requires knowing what terms were used in the period you are searching, rather than what the common, contemporary terms might be. This can be particularly challenging when searching for news about race and ethnicity, since much of the language describing such communities has evolved and changed throughout the centuries.

The **[Race and Ethnicity Keyword Thesaurus for Chronicling America](https://edsitement.neh.gov/media-resources/race-and-ethnicity-keyword-thesaurus-chronicling-america)** features a guide to searching topics of race and ethnicity in Chronicling America, including a thesaurus of words used in the past that may help produce more results. Primary documents from the past contain sensitive content, and the suggested keywords are often offensive to several different communities of people.

Created by partners in the [National Digital Newspaper Program](https://www.loc.gov/ndnp/awards/), this resource hopes to serve researchers at all levels through demonstrations and explanations of search terms related to race and ethnicity in Chronicling America.

More information can be found at the **[Race and Ethnicity Keyword Thesaurus for Chronicling America](https://edsitement.neh.gov/media-resources/race-and-ethnicity-keyword-thesaurus-chronicling-america)**.

---

## LOC.GOV API
The loc.gov application programming interface (API) provides structured data about Library of Congress collections in JSON and YAML formats. Software programs routinely access the JSON/YAML API to keep the loc.gov website updated as new digital content is added to the Library's collections. For example, JSON data is used to build loc.gov pages for items (loc.gov/item), collections (loc.gov/collections/), searches (loc.gov/search/), and more.

However, in addition to being a resource for the computer applications powering the loc.gov website, the API can be used by developers, digital librarians, and researchers to directly retrieve digital collections information formatted as JSON or YAML data.

### Access
The API is accessible to the public with no API key or authentication required.

> Additional information on the loc.gov API can be found at: [APIs for LoC.gov](https://www.loc.gov/apis/)

