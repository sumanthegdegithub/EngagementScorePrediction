# EngagementScorePrediction

### Problem Statement

ABC is an online content sharing platform that enables users to create, upload and share the  content in the form of videos. It includes videos from different genres like entertainment,  education, sports, technology and so on. The maximum duration of video is 10 minutes. 
Users can like, comment and share the videos on the platform.  
Based on the user’s interaction with the videos, engagement score is assigned to the video  with respect to each user. Engagement score defines how engaging the content of the video  is.  
Understanding the engagement score of the video improves the user’s interaction with the  platform. It defines the type of content that is appealing to the user and engages the larger  audience. 

### Feature Description

|Variable|Description|
| -------------- |:-------------:|
|row_id          | Unique identifier of the row|
|user_id         | Unique identifier of the user|
|category_id     |	Category of the video|
|video_id	Unique | identifier of the video|
|age             |	Age of the user|
|gender          |	Gender of the user (Male and Female)|
|profession      |	Profession of the user (Student, Working Professional, Other)|
|followers       |	No. of users following a particular category|
|views           |	Total views of the videos present in the particular category|
|engagement_score|	Engagement score of the video for a user|


### Evaluation Metric

![equation](https://bit.ly/3I7mol0)

### Approaches

There are mainly 2 approaches for this problem
- Regression
- Collaborative filtering


In this problem I have explored both the approaches
