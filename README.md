![image](https://github.com/rameshkumar359/youtube-warehousing-Analysis-Project/assets/96288285/fb079030-0840-4485-b65b-3c6fad4e3d04)# youtube-warehousing-Analysis-Project
![image](https://github.com/rameshkumar359/youtube-warehousing-Analysis-Project/assets/96288285/79455583-5cc4-454c-991a-188a8314f8ca)

YouTube Data Harvesting and Warehousing

Introduction

YouTube Data Harvesting and Warehousing is a project aimed at developing a user-friendly Streamlit application that leverages the power of the Google API to extract valuable information from YouTube channels. The extracted data is then stored in a MongoDB database, subsequently migrated to a SQL data warehouse, and made accessible for analysis and exploration within the Streamlit app.using plotly the application looks interactive and insightful.

Key Technologies and Skills

    Python scripting
    Data Collection
    API integration
    Streamlit
    Plotly
    Data Management using MongoDB (Atlas) and SQL
    Pandas dataframes

Installation

To run this project, you need to install the following packages:

pip install google-api-python-client
pip install pymongo
pip install pandas
pip install mysql.connector
pip install streamlit
pip install plotly

Usage

To use this project, follow these steps:

    Clone the repository: git clone https://github.com/gopiashokan/Youtube-Harvesting-and-Warehousing.git
    Install the required packages
    Run the Streamlit app: streamlit run stream.py
    Access the app in your browser at http://localhost:8501
    Create your own database for the cloud and Local server

Features

    Retrieve data from the YouTube API, including channel information, playlists, videos, and comments.
    Store the retrieved data in a MongoDB database.
    Migrate the data to a SQL data warehouse.
    Analyze and visualize data using Streamlit and Plotly.
    Perform queries on the SQL data warehouse.
    Gain insights into channel performance, video metrics, and more.

Retrieving data from the YouTube API

The project utilizes the Google API to retrieve comprehensive data from YouTube channels. The data includes information on channels, playlists, videos, and comments. By interacting with the Google API, we collect the data and merge it into a JSON file.

Storing data in MongoDB

The retrieved data is stored in a MongoDB database based on user authorization. If the data already exists in the database, it can be overwritten with user consent. This storage process ensures efficient data management and preservation, allowing for seamless handling of the collected data.

Migrating data to a SQL data warehouse

The application allows users to migrate data from MongoDB to a SQL data warehouse. Users can choose which channel's data to migrate. To ensure compatibility with a structured format, the data is cleansed using the powerful pandas library. Following data cleaning, the information is segregated into separate tables, including channels, playlists, videos, and comments, utilizing SQL queries.

Data Analysis

The project provides comprehensive data analysis capabilities using Plotly and Streamlit. With the integrated Plotly library, users can create interactive and visually appealing charts and graphs to gain insights from the collected data.

    Channel Analysis: Channel analysis includes insights on playlists, videos, subscribers, views, likes, comments, and durations. Gain a deep understanding of the channel's performance and audience engagement through detailed visualizations and summaries.

    Video Analysis: Video analysis focuses on views, likes, comments, and durations, enabling both an overall channel and specific channel perspectives. Leverage visual representations and metrics to extract valuable insights from individual videos.

Utilizing the power of Plotly, users can create various types of charts, including line charts, bar charts, scatter plots, pie charts, and more. These visualizations enhance the understanding of the data and make it easier to identify patterns, trends, and correlations.

The Streamlit app provides an intuitive interface to interact with the charts and explore the data visually. Users can customize the visualizations, filter data, and zoom in or out to focus on specific aspects of the analysis.

With the combined capabilities of Plotly and Streamlit, the Data Analysis section empowers users to uncover valuable insights and make data-driven decisions.

 ### project-demo link:https://www.youtube.com/watch?v=3zy_o9mCJ0A&t=294s
 ### linkedin-link:https://www.linkedin.com/in/ramesh-kumar-k-562891225/
