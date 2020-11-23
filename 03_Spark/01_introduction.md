# Introduction to Big Data

### 4V Definition
  - Volume: 
    - IBM predicted that data generated on 2020 will be 300 times of on 2005
  - Variety: 
    - More types of data can be collected for certain client, e.g. log, vedio/photo from social media
  - Velocity: 
    - data needs to be processed in a given time window, e.g. credit card fraud detection
  - Value: 
    - data should be able to bring new business oppertunities

### Big Data Source 

- People: social media; online purchasing, searching, gaming, etc. 
- Machine: server log, vehicle, location, weather, sensor, etc. 
- Business: email, text, image, audio, vedio, etc. 

### Data Types

- Structured data
- Unstructured data: document, email, vedio, etc.
- Semi-structured data: XML, JSON, etc. (After processing, they can be structured data.)

### Big Data Processing
- Parallel
- Scalable
- Processed fast 
- Can process different types of data

### Big Data Loop
Collection and store (HDFS, KAFKA) 
--> Processing (Spark, Flink)
--> Query (Presto, Hive)
--> ML model
--> Decision making 
--> Data collection and store again for a new loop 

### Common Use Case
 - Mobile payment
   - Paypal fraud detection
   - Wechat finacial product recommendation
 - Electronic business
   - Personalized recommendation in purchasing 
 - Vedio
  - Tiktok vedio analysis and recommendation 
  - Youtube vedio and advertisement recommendation 
