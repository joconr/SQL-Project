1. Project Name:
	TuneCore Spotify Playlist Analysis Project
2. Project Objective:
	a) The primary objective of this project was to figure out playlist KPIs that can be measured
based on the artists and their tracks on that playlist. I chose to solve this problem because TuneCore
currently has an underdeveloped program in which it tutors artists how to promote their music on programs 
such as Spotify. One of the primary ways of doing this is via official Spotify playlist pitches.

	b) I am solving this problem by determining playlist KPIs that drove popularity in that specific playlist. By determining the top artists in the playlist, 
connections can be made between their success in popularity on one playlist as opposed to others, their track duration, and more.

3. Job Description:
	a) TuneCore is a New York based independent digital music distribution, publishing and licensing service for artists around the globe. 
The title of the job posting I found was a Jr. Data Analyst. The description for this position was a person who "enjoys working in a dynamic fast-paced environment.
The ideal candidate will have an analytical mindset, an eagerness to learn and be comfortable with working under tight deadlines". In addition to this, role tasks include
but are not limited to creating, maintiaining and optimizing ETL processes used to prepare data for reporting and ad-hoc data requests, ingesting large data sets from 
digital music service providers (like Spotify) and conversion into APIs, and devoloping a cognitive understanding of the underlying revenue models reflected in the digital
music service providers reporting. 
	
	b) This project is related to the TuneCore job posting in that it is working closely with Spotify data that will most likely be used in revenue models provided to 
TuneCore. The KPIs I am measuring also provide insight into building a more effective tutoring program for TuneCore artists that will help them design songs that are more likely
to gain more streams and, in turn, revenue from Spotify.

4. Data:
	a) The source of all data used for this project came from the Spotify for Developers API (https://developer.spotify.com/documentation/web-api/)

	b) The characteristics of the data used in this project include track names, artists, song duration, explicit nature, song URLs, and albums across three different
indie rock playlists that I chose for the sake of the sake of focusing on one genre of music.

5. Notebooks:
	a) Data Collection Notebook: https://github.com/joconr/SQL-Project/blob/main/data_collection.ipynb
		This notebook contains code that was used to pull necessary data from the Spotify API. The code was re-used to enter data into three separate tables at a time.

	   SQL Analysis Notebook: https://github.com/joconr/SQL-Project/blob/main/sql_analysis.ipynb
		This notebook contains SQL queries that were performed to determine playlist KPIs. Alongside the code, there is also insights into the next steps that 
		can be taken based on the results.

6. Future Improvements:
	a) While I'm proud of the results I gathered from the data I colleceted, there are a few things I would have done differently while collecting the data. The first 
	   thing I would have done was go back and figure out a more efficient way of collecting data on the actual stream counts for each song (beyond the playlists). Because
	   of Spotify's security measures and web layout, it proved to be difficult to web scrape that data. I believe with a bit more time and other web resources, I could have
	   gathered this data, and it would have been very useful to use for other KPIs related to actual revenue being earned by artists. 