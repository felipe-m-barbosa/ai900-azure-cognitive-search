# ai900-azure-cognitive-search


First things first. What the Azure Cognitive Search is?
It is Azure's platform for knowledge/data mining that runs on top of AI.

For a search in the Cognitive Search to be effective, we need:
* Data Ingestion:
  * Azure Blob Storage containers
  * Azure Data Lake Storage Gen2
  * Azure Table Storage
* Data enrichment and index: makes data more useful for searching
  * Allows for a deeper understanding
  * Computer Vision, NLP, ...
  * Content indexing so that to become searchable
* Explore
  * Index-based search
  * Inside apps
  * Create data visualizations

### How to configure a search?
  1) Create an AI Search service
  2) Create an AI Services service
  3) Create an Storage account
  4) Upload the files to the storage
  5) Go to the AI Search and import data from the Storage (link the AI Search to the Storage)
  6) Search using the AI Service to automate it

### Possible tools that may benefit from the Azure Cognitive Search:
  Any tools that need to perform sentiment/opinion analysis, such as stores, restaurants, hotels, and so on...
  
  It is also possible to perform inference based on vision so that to count and recover the number of people that entered in a given store, or crossed a given street, in order to track the times of the day in which the store or even certain parts of the city are more crowded.
