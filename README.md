# CMD Search Application (Cheatsheet)

### What's the whole plan?
* Scraping commands from different websites
* Labeling those data for AI or ML training
* Implementing search engine for cheatsheet of commands

### What we did right now?
* Implemented search using Apache Solr (Inverted Index based search engine)(✅)
* Developing full stack application in next.js(✅)
* Scrapping data from website and seeding to solr (❌)
* till now some data is seeded to solr(📈)
## Installation

Go inside of the solr folder and locate the bin folder and run following command to start apache solr(window user)

```bash
./solr start
```
then solr will start at [solr home](localhost:8983)

then go inside of full stack folder cheat_sheet_web_app and run following command
```npm
npm run install
npm run build
npm run start
```
## Usage
Then browse to [localhost:3000](localhost:3000)
now you are good to go
