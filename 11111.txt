Let's imagine mobile application that receives traffic from different sources. This traffic is not homogeneous and we need to know it better in order to optimize marketing activity

Your task is to analyze dataset in order to find useful insights: what segments of data bring traffic with the best quality (Main metric is conversion rate from lead to client. There can be other metrics as well) 


You can do this by answering following questions:
-How users are distributed over countries?
-How many outliers are there in data (in terms of deposits)?
-Find segments with best conversion rate (client/lead ratio) and explain why you consider them best ones
-Visualize deposits distribution over sources and channels
-What are your advices to marketing team in order to optimize their activity?

To do this you have a synthetic dataset that contains history of users' activities (registrations and deposits)
Data description: client_id - unique id of lead/client. it's assigned during registration and isn't changed anymore 
Country - country of lead/client (iso2). It's in the separate file (countries.csv)
Source - source of traffic acquisition. There are two possible sources (posts and telegram channel). if Source contains "postid" - it means that lead came from article. id of post doesn't matter. if Source contains "telegram" - it means that lead came from telegram  
channel - channel of traffic. For example, user can come from 'telegram' source and from 'affiliate' channel
Clicks - amount of clicks user made during first day after registration
Latency - time of application loading in miliseconds
Depo - amount of deposit, USD



Expected result is Jupyter notebook with Python code showing answers to questions above

Glossary:
Lead: user who registered inside mobile app
Client: user who registered inside mobile app AND made a deposit