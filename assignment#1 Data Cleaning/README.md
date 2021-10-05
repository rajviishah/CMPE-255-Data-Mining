**Data Cleaning - Trending YouTube Video Statistics Dataset**

Data Collection:- 
Dataset:- https://www.kaggle.com/datasnaek/youtube-new

About dataset:-

This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included for the US, GB, DE, CA, and FR regions (USA, Great Britain, Germany, Canada, and France, respectively), with up to 200 listed trending videos per day.

Here, I have cleaned data for US region. 

There are two kinds of data files, one includes comments and one includes video statistics. They are linked by the unique video_id field.

The headers in the video file are:

- video_id (Common id field to both comment and video csv files)
- title
- channel_title
- category_id (Can be looked up using the included JSON files, but varies per region so use the appropriate JSON file for the CSV file's country)
- tags (Separated by | character, [none] is displayed if there are no tags)
- views
- likes
- dislikes
- thumbnail_link
- date (Formatted like so: [day].[month])

The headers in the comments file are:

- video_id (Common id field to both comment and video csv files)
- comment_text
- likes
- replies


