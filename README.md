
# Youtube data analysis 

Here I've selected some 126 channels from Youtube and harvested their public data from the YouTube Data API v3.
Considering the API's limitations and some data cleaning I've made, it has yield some 109.845 videos with the following variables:
- channel_title
- channel_id
- video_title
- video_id
- video_upload_date
- views
- likes
- dislikes
- comments
- age_days
- likes_dislikes_ratio
- comments_views_ratio
- mean_views_day

Then I've done some interactive plots with ipywidgets for the user to enjoy exploring the data for each channel or even comparing two channels at once.

Feel free to grow and update the dataset, baring in mind the API's limitation of only 20.000 videos by channel.

Have fun!

## Figures:

![screen 1](Figs/1D_Histogram.png)
![screen 2](Figs/2D_Density.png)
![screen 3](Figs/Barplot_Channels.png)
![screen 4](Figs/Bubble_Colors.png)
![screen 5](Figs/Correlation_Matrix.png)
![screen 6](Figs/Scatter_2_Channels.png)
![screen 7](Figs/Scatter_Colors.png)


