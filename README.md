# Whatsapp Chat Analysis
WhatsApp Chat Analyzer analyses WhatsApp group chats as well as personal chats. It gives daily, weekly, and monthly analysis of personal chats, groups, or individual people in the group.

### Challenges

- The first challenge of the project was to convert the text file to a Pandas dataframe. Initially, I separated the date and time from the text. The separation of time from the text data was done by using the Regex function.
- After the date and time, the username and notifications had to be separated from the text, which was done again by looping the text file and using the regex function.
- Finally, the date column was converted to a date time datatype, and pandas was used to separate the minutes, hours, dates, month, and year.

![image](https://user-images.githubusercontent.com/102586176/217316951-ba1ee911-4438-4425-b4fc-410d97dca85c.png)

### Visualization

**Top Statistics:** This contains the total number of messages, total number of words, and total number of media and links shared in the chat.

**Daily Timeline:** It is a line graph of the daily activity in the group.

**Activity Map:** The first bar graph contains the most active days of the week, and the second bar graph contains the most active month of the year.

**Monthly Timlines:** It determines the monthly activeness of the group or of an individual.

**Most Active Users:** This gives us the dataframe and bar chart of the users who are most active in the group. The dataframe contains each individual's activity percentage relative to the group's total activity.

**Most Common Words:** This displays the top 20 most used words in the whole chat in bar chart format.

**Emoji Analysis:** The top five most used emoji are presented in dataset format as well as in a pie chart to present the data visually.

**Weekly Activity Map:** This is a heat map that indicates when the group or an individual is most active (both in terms of time and day).

### Web application and deployment

The web app was simultaneously developed on **Streamlit** and then deployed on **Render**.

- Deployed Project Demo: https://whatsapp-chat-analysis-54xa.onrender.com

- Project Working: https://youtu.be/xffjzPka0z0
