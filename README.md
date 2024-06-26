# Live Generative AI demo with Open AI - ChatGPT 4, Kafka, MongoDB Atlas Vector Search and D-ID

## Architecture:
![architecture](./architecture2.png)   
   
## Initial Setup:
* (install express) open a terminal in the folder and run  - npm install express
* Add additional npm installs for what is missing in app.js
* run - npm i cors
* run - npm i express http-proxy-middleware
* run - npm i express morgan
* Pay attention to the rewrite rules in app.js and update for your MongoDB Atlas and Confluent Cloud Environments
* (add your api keys) edit the `api.json` inside the uncompressed folder and replace the emoji with your key
* When running the app.js at http://localhost:3000 press the "Open Settings" button and add in your D-ID and Open AI API keys.


## Start the demo:
* (bring up the app) in the folder (ctr left click on folder through finder) open the terminal run node app.js 
* You should see this message - server started on port localhost:3000
* (open the app) in the browser add localhost:3000
* (connect) press connect you should see the connection ready 
* (stream) press the start button to start streaming   
    

|Franz Kafka Introduction Video|    
|---------------------------|   
|[Click here to watch a 7 Minute Video on what you will create](https://youtu.be/pLU7dS9DJJg)|   
|<a href="https://youtu.be/pLU7dS9DJJg" target="video"><img src="https://img.youtube.com/vi/pLU7dS9DJJg/0.jpg" width="1080px"></a>|   


## MongoDB Tutorials & Blogs
[Node Tutorial](https://www.mongodb.com/developer/products/atlas/semantic-search-mongodb-atlas-vector-search/)   
[Python Tutorial](https://www.mongodb.com/developer/products/atlas/building-generative-ai-applications-vector-search-open-source-models/)   
[MongoDB & Confluent Partner Blog](https://www.mongodb.com/blog/post/mongodb-atlas-vector-search-makes-real-time-ai-reality-confluent)  

## MongoDB Data Set
[Fashion Data Set](https://github.com/afsungur/mongodb-atlas-vector-search-fashion-products)

## Backend QNA Service
Github for back end QNA microservice that performs the Vector search in MongoDB Atlas and returns the results to the digital assistant app is here:   
[Backend QNA Service](https://github.com/ashwin-gangadhar-mdb/mdb-ecomm-recsys-chatapp/tree/main/backend)

## Aditional Code Examples
Data Augmentation how to vector encode product and inventory data using Confluent Cloud in real-time and update MongoDB for continuously updated vector embeddings:   
[Gen AI First Step: RAG Data Augmentation for Gen AI: Building your Vector Database](https://github.com/brittonlaroche/Confluent-Kafka-Vector-Encoding/)

GenAI Demo with Kafka, Flink, LangChain and OpenAI   
[Kai Waehner Blog](https://www.kai-waehner.de/blog/2024/01/29/genai-demo-with-kafka-flink-langchain-and-openai/)   

Demo: LangChain + Kafka + Flink = Automated Cold Calls of Sales Leads with Salesforce CRM and LinkedIn Data      
[Carsten Muetzlitz Github](https://github.com/ora0600/genai-with-confluent/tree/main)

## Video
[Youtube Application Demo](https://youtu.be/9thD4128lDE)

## App:
![app](./app3.png)

## Settings
Set your OpenAI API key and D-ID Key by opening the settings window.  Press the "Open Settings" button at the top of the application
![image](https://github.com/brittonlaroche/GenAI-ChatGPT4-Confluent-MongoDB-Vector-Retail/assets/32334829/a0e27be0-132e-4219-ab7d-fd306ee79275)

![image](https://github.com/brittonlaroche/GenAI-ChatGPT4-Confluent-MongoDB-Vector-Retail/assets/32334829/9709475e-555f-481a-9ed3-96baa1ece1f3)
