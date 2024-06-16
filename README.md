VIEW RENDERED JUPYTER NOTEBOOK HERE: https://nbviewer.org/github/noreplyprofiles/daily_social_media_usage_contributing_factors/blob/main/Daily%20Social%20Media%20Usage%27s%20Contributing%20Factors.ipynb

In the modern day, most students resort to social media as a form of entertainment whenever they are bored. With apps such as TikTok and Instagram, it is very easy to spend hours on end browsing through social media. While many studies show data regarding the relationship between social media usage and emotional states, I have not come across many regarding what influences daily social media usage time. For this project, I will be observing how various factors can affect the amount of time a person spends on social media through a linear regression model.

The dataset I will be using for this project is regarding Social Media Usage and Emotional Well-Being.

Here is the link to the dataset: https://www.kaggle.com/datasets/emirhanai/social-media-usage-and-emotional-well-being?select=test.csv

The dataset contains 10 columns:
- User ID: an identifying number for each user in the dataset
- Age: the age of the user
- Gender: the gender identity of each user (male, female); NOTE: A third option for gender existed, however, it has been dropped for this project to only focus on males and females
- Platform: the main social media platform in use (Instagram, Twitter, Facebook, LinkedIn, Snapchat, Whatsapp, Telegram)
- Daily Usage Time (Minutes): total minutes spent per day on the platform
- Posts Per Day: number of posts created per day
- Likes Received Per Day: number of likes received on posts per day
- Comments Received Per Day: number of comments received on posts per day
- Messages Sent Per Day: number of messages sent per day
- Dominant Emotion: the most common emotional state of the user during the day (Happiness, Sadness, Anger, Anxiety, Boredom, Neutral)

As mentiond previously, I will be focusing on Daily Usage Time as my target variable (dependent variable).